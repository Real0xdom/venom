venom
===============

USB / CD / DVD autorun password stealer for Penetration Tests.

This repo will help you create a proper autorun usb which steals passwords, browser history, along with giving you reverse connection to your attacker machine from the target device where you've plugged in the usb. Code is well documented, feel free to modify for your own personal use.

Test in a lab environment. Use at your own risk =) 

Follow the steps given below

step 1: clone this repo

step 2: (this step will work in windows) install the autoruncreator.exe in this repo

step 3: once the program is started specify the .bat file in first field and in the second field specify the usb drive which you want to autorun.


however the launch.bat won't work if you made changes to the lauch.bat file because the information of .bat file is stored in openfile created after you make your pendrive autorun with autoruncreator.exe, so the launch.bat file should be the exact file when it was selected during the creation of autorun with the program. 
there is workaround tho if you wanna modify .bat file modify it and make it to autorun with that autoruncreator.exe program this way you can use your own .bat file
