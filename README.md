# usb-botbase based on sys-botbase
The purpose of this sys-module is to allow users to remote control their switch via usb connection as well as to read and write to a games memory. This can be used to create bots for games and other fun automation projects.

## Warning:
Don't even think of blaming me if anything goes wrong with you using this. It's supposed to help you in the development of bot automation, but I am not liable for any damages or bans you might get in the process. Use at your own risk and all that.

# Easy Installation
Download the .zip file and extract it to your sd card. The zip file contains the necessary folder structure and flag files.
Restart your switch. 

# Manual Installation
Copy the sys-botbase.nsp file to sdmc://atmosphere/contents/430000000000000B and rename it to exefs.nsp.
Create a new folder in sdmc://atmosphere/contents/430000000000000B names "flags".
Create a empty file called boot2.flag inside this folder.
Restart your switch.

The sysmodule opens a socket connection on port 6000. See the python example on how to talk to the sysmodule and what commands are available.


# Credits
Main Credits goes to olliz0r. This is a fork of his repo.
