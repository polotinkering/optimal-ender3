Klipper
---
What an interesting modification !  
some will be surprised that i don't put it on [S] tier but i feel like you can have some really good results with the classic marlin firmware .
I want to adress a big thanks to [JSTECH](https://www.youtube.com/@Jstech3d) and all of his discord for the support and the help while setting up klipper .  
So I have used a raspberry pi 2b with the [fluidd](https://docs.fluidd.xyz/) interface .
I have struggle a lot during the setup of the wifi dongle so i share my mistakes to avoid you hours of troubleshooting:
- 1 wrong usb dongle .I was trying a 5v TP-link wifi dongle and the rapi only supply 3v .[here](https://elinux.org/RPi_USB_Wi-Fi_Adapters) is the list of compatibles dongles .
- 2 I was using a fluidd pi image instead of a classic os and it is not compatibles with external usb .[This video](https://www.youtube.com/watch?v=oM2kAnITNyE&t=190s) can be usefull for wifi setup.

So i went with a raspbian lite image that i have flashed through the [raspberry pi imager](https://www.raspberrypi.com/software/)on my sd card.  
After this I have put the sd card in the pi and connected it via SSH with [putty](https://www.putty.org/)
Now you can follow the [kiauh documentation](https://github.com/th33xitus/kiauh)it simply consist on pasting commands on the console .
you need to install :
- klipper 
- moonraker
- a web interface : mainsail or fluidd *I have choose fluidd*
after you need a "printer.cfg" file i have shared mine in the files section of this folder .
this is my interface:
![fluidd](https://github.com/polotinkering/optimal-ender3/assets/133749952/80b7a566-8e9d-45e8-bd53-932f20e9f6e0)
