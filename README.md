# ASUS-Crosshair-VIII-Impact-EFI
Complete EFI Folder for Catalina 10.15.4
Built using Opencore 0.5.7

SMBIOS information has been randomized, you should use a tool such as https://github.com/corpnewt/GenSMBIOS to fill in your MLB, System Serial Number, and UUID. Use iMacPro1,1 when generating a new SMBIOS.

Use this guide to fix your ROM (Just set your mac address) https://dortania.github.io/OpenCore-Desktop-Guide/post-install/iservices.html

This is a graphical final release, if you are encountering issues, go into the boot arguements and re-add -v for verbose mode.

This EFI is untested with the original AX series WIFI card. I've heard from another member that Bluetooth will work, but wifi didnt. It can probably be used with additional kexts. 

I recommend making a USB map, one of my front USB 3 ports do not work, but all others are operational.
