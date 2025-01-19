
# Bambu lab network plugin and firmware backup

Due to Bambu lab's decision to lock down third party integrations I decided to make a backup of the current network plugin and firmware for all of their printers.

This might be useful in the future if they decide to make them unavailable.

A short guide on taking your printer offline (disconnecting it from their cloud and using LAN only mode): https://tzeny.com/2025/01/19/lan-mode-with-live-view-remote-monitoring-control-and-blocked-internet-a-short-guide/

## Contents

### Firmware (Firmware\)

The firmware folder contains all the latest firmware that work with third party apps downloaded directly from Bambu's website (ex: https://bambulab.com/en/support/firmware-download/p1).

They are named <printer_model>_<firmware_name>.zip

### Network Plugins

#### Windows (NetworkPlugin\Windows)

In order to communicate with the printer both Bambu Studio and Orca Slicer use a network plugin. I made a backup of the plugin folders for both of them on my Windows machine (%APPDATA%/Roaming).

#### CDN (NetworkPlugin\CDN)

I also downloaded the plugins for Windows, Linux and macOS from their CDN https://public-cdn.bambulab.com/upgrade/studio/plugins/01.07.01.04/win_01.07.01.04.zip , https://public-cdn.bambulab.com/upgrade/studio/plugins/01.07.01.04/linux_01.07.01.04.zip, https://public-cdn.bambulab.com/upgrade/studio/plugins/01.07.01.04/macos_01.07.01.04.zip .

They have different file sized compared to my own, but I think it is important to maintain backups of all of them.

## The cause of all this

Rosmanngroup's Wiki documents the problems with Bambu's latest firmware which is basically anti consumer: https://wiki.rossmanngroup.com/wiki/Bambu_Lab_Authorization_Control_System .

I also recommend this Reddit post explaining why you should care and what you can do about it: https://www.reddit.com/r/BambuLab/comments/1i3gq1t/why_you_should_care_about_bambu_labs_removing/ .

# Contributing

Make a PR or contact me to add versions of the plugins for other OSs that you have on your machine and are working right now.



