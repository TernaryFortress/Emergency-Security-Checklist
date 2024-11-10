# Preparation:
Before you go diving into your devices, we want to ensure that your software is safe.

You want to download the following software from two different sources, if able:
1: Modem firmware
2: Router firmware
3: Operating system

Your best bet is to seek software from a place with enterprise-grade security.


If you are forced to download software locally, you can attempt to install both a VPN app and a browser, from a reputable app store. This may not be enough, depending on . In either circumstance, you should do your best to cross-verify the application's authenticity by running checksums on both files.

To verify a checksum, first checkopen Windows Powershell via the start menu.
! Full paranoia mode ! - First, unplug your computer from the internet, and close any browsers
In Windows Powershell, type the following: Get-FileHash -Path "filename" -Algorithm SHA256
Where "filename" is the path of your file.
Note: You do not have to manually type the filename, you can just drag the file into the terminal when you get to that point.

Ensure that
