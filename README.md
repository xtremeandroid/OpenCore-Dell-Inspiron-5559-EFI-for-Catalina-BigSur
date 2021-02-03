# OpenCore-Dell-Inspiron-5559-EFI-for-Catalina-BigSur
NOTE:
    :
    :
    :
    You Should only Update to BigSur After Successfully Booting and Fixing Catalina
    remember to update all kexts and opencore to latest versions (in EFI Folder)
    to run BigSur Stable

Experience/Review :
I Recommend catalina for this laptop it is really snappy but BigSur is not snappy it freezes at times
on my HDD Atleast
Boot Time was Around 55 SEcs with Catalina
and 1 Min  5 Sec with BigSur

System's Configuration:
Laptop Dell Inspiron 5559 (Indian Version it is but should work for everyone wit same specs)
Specifications	Details
Laptop Model	Dell Inspiron 5559
Processor	Intel Core i7-6500U @ 3.10GHz dual-core
RAM	2 X 8GB (SK Hynix DDR3L 1600MHz + Kingston DDR3L 8GB)
Storage	HDD - WDCWD10 1TB
Graphics	Intel HD Graphics 520
Display	LED HD 1366x768 (15.6 inches)
Network Card	Network Card: Intel Dual Band Wireless-AC 3160 HMC WiFi Adapter
macOS Catatlina 10.15.6
OpenCore 0.5.9(Easily Upgradable)
Setup
Download GibMacOS and Run it
Toggle Recovery mode by pressing R
Then select latest version of catalina with full install written aside it
insert your usb (should be 8 GB+)
and run make install from GibMacOS Folder
select your drive with aside it
for example
your drive no is 1
write 1o
(it is O not ZERO)
then

Copy folder EFI from this repo and paste in your boot's usb
Ok & install now
Fix some kext:

TO Fix Wifi: download the lastest Heliport release at OpenIntelWireless's Repo & download the lastest itlwm kext. Using Proper Tree to update config.plist file. Install Heliport.dmg and open, then goto System Preferences -> Users & Groups -> select Current User and add Heliport to Login Items.

Remember Wifi is Buggy (it is connected all the time but performs like shit i get maximum 7-10 mbps on my 200 mbps Broadband ALso 5GHZ is not Supported)
I Recommend Buying an External One from TP-Link with MACOS Support

Scrolling on trackpad & mouse: if you can't setup scrolling direction as windows os (trackpad: natural, mouse: non-natrual). Following steps:
Download Mos
Setup like following picture setup Mos

Not working
Amd Radeon R5 M335
P/s: If you would like any further information, please don't hesitate to create new issues on this git
EFI Pre Configured For Dell Inspiron 5559 EFI for Catalina/BigSur

