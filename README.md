# Crouton-OS
This adds crouton and SeaBIOS to any Chrome OS or Chromium OS based computer.


Steps - 

1 - Unzip package in Chrome OS or Chromium OS device

2 - Pull crouton file into downloads section

3 - press Ctrl+Alt+T to open crosh

4 - type shell

5 - 
  A* - type sudo sh ~/Downloads/crouton -r list
    -choose your operating system from the list
    -type sudo sh ~/Downloads/crouton -r xenial(or whatever OS you chose) -t list
    -choose your desktop environment from the list
    -type sudo sh ~/Downloads/crouton -r xenial(or whatever OS you chose) -t unity-desktop (or whatever desktop environment you chose)
    -if you have a password for your chroots, it will prompt you for your password
    -it should start downloading
    -it will prompt you for a username and password in between the download. When you see blue text, it is prompting you for a username. Type your username and press ENTER. After that, it will prompt you for a password. Type your password and press ENTER. Then It will ask you to verify your password. Type it again and press ENTER. After that, it should finish the download.
    - to start your new OS, type, in shell, sudo startunity(or whatever desktop environment you chose. For Unity-desktop, type sudo startunity).
    B* - type sudo sh ~/Downloads/crouton -r xenial -t unity-desktop
     - follow the steps after step 4 for A
    
6 - in Chrome OS Shell, type cd; curl -LO https://mrchromebox.tech/firmware-util.sh && sudo bash firmware-util.sh for SeaBIOS
  - when a table with device information shows up, press 1
  - when a yes or no question comes up, type y
  - when prompted to, press ENTER
  - then press q
  - now whenever you plug in a bootable removable storage device (like a USB drive), hold down Ctrl+L on the developer screen and it should take you to SeaBIOS. Navigate and choose your removable device, like you would on a regular Windows BIOS, and it will boot from the removable storage with any OS*.
  
7 - A* - only for advanced users
8 - B* - for any users
9 - OS* - WP Screw has to be unscrewed for Windows to boot
