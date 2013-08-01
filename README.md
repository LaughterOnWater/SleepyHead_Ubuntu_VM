SleepyHead Ubuntu VM
====================

This is the git repository for a VirtualBox Ubuntu 13.04 virtual machine with SleepyHead 0.9.2  It should work in any platform capable of using VirtualBox.
This is a 64-Bit Virtual Machine. It will not work on a 32-bit machine.
This is the latest linux .deb of SleepyHead on the latest version of Ubuntu as of the creation date of this file.

Author: Chris (DreamDiver) <c@low.li>

Website: http://low.li

Creation Date: 7/30/2013

*TO INSTALL*

1. Install Virtual Box for your operating system.
2. Install 7zip for your operating system, a very good archiving application.
3. Download the .7z compressed virtual disk here: http://dreamdiver.org/wp-content/uploads/2013/08/SleepyHead_Ubuntu_VM.7z
4. Unzip the virtual machine where you want it to live. Once you pick a spot, it's best to leave it there, so choose wisely.
5. Double click on the SleepyHead_Ubuntu.vbox file. It should open up. Please be patient.
6. Soon you will see the desktop. The Launch pad bar is on the left side of the screen. The third icon from the top is SleepyHead. Click it once. If the icon just "glows" at you and doesn't bring up the new-user prompt, please be patient and try again in a few seconds.
7. Follow the prompts for adding yourself as the first user. You can leave as much as you want of this blank.
8. Select your user. Sleepyhead should now open up, ready for data import.
9. Next time you use SleepyHead, it should automatically select the first user, if you're the only user. You'll only have to click "Select User".
10. To shut down Ubuntu, use the power pulldown menu in the top right corner of the desktop, the click "Shut Down" in the dialog box that pops up. In a few seconds, your machine will be shut down.

*VIRTUAL MACHINE PARTICULARS*

This virtual machine is a clone of one I set up this way:
2GB RAM
64MB Video RAM
8GB Hard Drive
2 Processors
VboxGuestAdditions is installed.

User: Ubuntu
Password: SleepyHead
Password is not required when it boots up.

The above system settings allow the VM to run reasonably fast, but if you want a faster experience, you could try adding more RAM and Video RAM and processors, depending on how much your native operating system can handle.

If you already have Ubuntu with SleepyHead installed and you just want a handy icon to load without using terminal, try this:

1. Download SleepyHead_Icon.zip to your home folder.
2. Open terminal.
3. cd /home/user/SleepyHead
4. Edit in nano: $ nano SleepyHead.desktop (The file extension '.desktop' remains invisible while viewing in the gnome window interface. You will see it when you navigate there in terminal.)
5. For each of the two lines where it says: "/home/ubuntu/SleepyHead/", change the user name from "ubuntu" to your user name.
That's all there is to it.
6. Close terminal.
7. Open the home folder in a gnome window and navigate to SleepyHead folder.
8. Drag the file labeled "SleepyHead" carefully to the Launcher bar between two existing icons. Once a space opens up for the new icon, release your mouse. (Do not drag either file ending in .sh or .ico.)
You now have an icon linked to sleepyhead on your Ubuntu desktop.

*LICENSE*

SleepyHead and Ubuntu are opensource projects, each subject to their own distribution rights considerations. Please see their respective websites for information about distribution rights, but as far as I know you can use this distrubution as you see fit.

SleepyHead:
http://sleepyhead.sourceforge.net

Ubuntu:
http://www.ubuntu.com/download/desktop

Laughter On Water:
http://low.li

DreamDiver:
http://dreamdiver.org

VirtualBox:
https://www.virtualbox.org

7-Zip:
http://www.7-zip.org
