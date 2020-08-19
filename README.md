# Dell-E7440
If you also own Dell Latitiude E7440 then you can use this EFI Configuration in your E7440 after installing Hackintosh Mojave.
You can download Hackintosh Mojave from `getintopc.com` I have used `Niresh Hackintosh Mojave` for reference you can use the same.
If you don't know anything about what Hackintosh is then you must read about it on Google.

# Steps to install Hackintosh 
1. You need to ensure hardware compatibilty if you donot own E7440.
2. You must have a USB which is more than 8Gib or atleast 8Gib.
3. Download and install `TransMac` from the link from here `https://www.acutesystems.com/scrtm.htm`.
4. Download the Niresh Hackintosh Mojave `dmg` from `https://getintopc.com/softwares/operating-systems/niresh-mojave-hackintosh-dmg-free-download-1726447/` this link.
5. Open Transmac as administrator and connect your USB Flash Drive.
6. After that Rightclick on the Flash Drive you inserted in the Transmac list and Format the drive for mac.
7. Now again Rightclick and click Restore option and locate the Hackintosh DMG you downloaded.
8. Now after this is done it might take a while sit and relax.
9. Restart your laptop and before that just copy my git files.
10. Open BIOS and disable all the security options.
11. Boot via your Flash Drive.
12. Boot Hackintosh installer.
13. Now open Disk Utility and format your internal or external harddrive/ssd for MAC as APFS partition type.
14. Install the Mac.
15. Your system might boot during the install.
16. Now after install again boot into your usb drive but now boot into the drive in which you installed your Hackintosh.
17. Setup your Hackintosh via offline installer.
18. As wifi will not work so after this connect Ethernet and download Clover Configurator.
19. Open Clover Configurator and Mount the EFI partition of the Drive your installed your Hack on.
20. Now copy my EFI Folder and overrite it with the one system created.
21. You have created your Hackintosh successfully.
22. Now try booting in your Hac without USB.
23. If something doesnot work then search for the respective `kexts` i.e. drivers.

# Good Luck
# On My Laptop everything works except Wifi and Bluetooth.

# List of the kexts which can be usedful 
Appleps2controller

Lilu

USBinjectall

Whatevergreen

AppleALC 

FakePCIID_Intel_HD_Graphics

SMCBatterymanager

BrcmFirmwarerepo

Brcmpatchram

CodecCommander

DisableTurboBoostBattery

