This adds SeaBIOS to any Chrome OS or Chromium OS based computer.



1 - press Ctrl+Alt+T to open crosh

2 - type shell*

3 - in Chrome OS Shell, type cd; curl -LO https://mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh for SeaBIOS
   - when a table with device information shows up, press 1
   - when a yes or no question comes up, type y
   - when prompted to, press ENTER
   - then press q
   - now whenever you plug in a bootable removable storage device (like a USB drive), hold down Ctrl+L on the developer screen and it should take you to SeaBIOS. Navigate and choose your removable device, like you would on a regular Windows BIOS, and it will boot from the removable storage with any OS*.
   
 4 - OS* - WP Screw has to be unscrewed for Windows to boot 
 
 5 - shell* - developer mode should be enabled for this to work
