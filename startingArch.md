##### -rwxrwx--- [knownconfigurations.sh](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/scripts/files/stable/knownconfigurations.sh)

##### -rwxrwx--- [necessaryfunctions.sh](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/scripts/files/stable/necessaryfunctions.sh)

##### -rwxrwx--- [printoutstatements.sh](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/scripts/files/stable/printoutstatements.sh)

##### -rwxrwx--- [setupTermuxArch.sh](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/scripts/files/stable/setupTermuxArch.sh)

##### -rwxrwx--- [setupTermuxArch.tar.gz](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/scripts/files/stable/setupTermuxArch.tar.gz)

##### -rwxrwx--- [archsystemconfigs.sh](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/scripts/files/stable/archsystemconfigs.sh)

## __There are a number of ways you can start Arch Linux in Termux once installed.  Three methods of starting Arch Linux in Termux after installing are outlined here:__

1)  Run `~/arch/startarch` at the bash prompt.  The **bash shell interpreter is important!**

2)  Run `startarch` if you chose "copy to $PATH" during install.  The **bash shell interpreter is important!**

3)  Run `chsh` and change your login shell to `startarch`.  Option 2 is required for this option to run correctly.  When you open a session in Termux, it will login to Arch Linux.  **Important** to undo this change and return to your Termux login, delete `.termux/shell` since `chsh` will be unavailable in Arch Linux to change your login shell.  

These are three options. Certainly there a more ways to start an Arch Linux login in Termux on device.  For the beginner CLI (Command Line Interface) user, option 2 "copy to $PATH during install" is recommended.  Enjoy running Arch Linux in Termux on your device 📲 

