# iGPUHackintosh
A short guide for a Catalina Intel 9700k Hackintosh with an iGPU

1. Create a bootable USB for Catalina using GibMacOS on a windows PC
2. Paste everything in this git directory into the folder that should be AUTOMATICALLY mounted into file explorer
3. Boot the PC, go into the bios, and load "F8c" settings as your configuration. It's in the rightmomst menu. Please note, this is for firmware F8C so it will only load into boards running that firmware. IF you don't have the F8C firmware, make sure to check around the bios settings and disable all safety boot settings, all fast boot settings, and all windows fast boot features.
4. Save the new configuration and restart. Press MacOS Environment which will then boot into the Mac recovery software.
5. Attach an ethernet cable (or a USB WiFi adapter, although I haven't tried that myself) and hit install MacOS catalina
6. Watch it install, it should shut down afterwards and then you should see the new MacOS partition in your Opencore boot menu.

For any questions, either add an issue on this repo, or go to https://www.reddit.com/r/hackintosh/comments/jxd8ey/success_9700k_auros_pro_wifi_itx_z390_igpu/

