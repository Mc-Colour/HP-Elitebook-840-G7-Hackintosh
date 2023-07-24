# HP-Elitebook-840-G7-Hackintosh
Created for Monterey, works with ventura however you will need to replace the airportitlwm kext with the latest ventura specific one, otherwise bluetooth and wireless will not work.

## Setup
* Follow the dorthania guide on downloading recovery image and creating USB: https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
* Grab the EFI folder (and update airportitlwm if install Ventura) and paste it in root directory of USB.
* Install Mac OS (ensure disk is formatted using APFS).
* Reboot, use tools shown in guide above to mount EFI of the new install after reboot and copy over the EFI folder.
* You can now reboot and remove USB

## WORKING
* WiFi
* Bluetooth
* Speakers
* iCloud
* Touchpad
* Keyoard
* Anything that isn't specified below

## NOT WORKING
* Sleep
* Microphones
* Camera

## NOT TESTED
* Fingerprint scanner
