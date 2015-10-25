####ubuntupackages
=============================================
![](http://www.muylinux.com/wp-content/uploads/2015/05/wiliwerewolf.jpg)

Compatible with any Debian based system:

Ubuntu, Xubuntu, Ubuntu MATE, Linux Mint, Kubuntu, Lubuntu, Ubuntu Kylin, Edubuntu...

Porting to 15.10 (Wily Werewolf). Not all the 3rd party are compatible with 15.10. In process to solve it.

Instructions
=============================================
Do a backup of your "/etc/apt/sources.list.d" folder. Coming soon automatic...
Read the code and do your modifications.

Then do these basics steps:

1.Go to your selected script and modify it.

* "installpackages1" if you want to install some basic packages.
* "installpackages2" if you want to check my extra installed packages.
* "installpackages3" if you want to check my extra proposed packages.
* "installpackages4" if you want to check more extra packages.
* "installpackages5" if you want to check the test packages.
* "installpackages6" if you want to check problematic packages.
* "installpackages7" if you want to check more alternative modes to install packages. To test yet.

* "nu-installpackages1" if you want to install some basic packages for normal users.
* "nu-installpackages2" if you want to install more basic packages for normal users.

2. Execute it.

Remember to add exec permissions to all scripts!

"sudo chmod 777 archiveName"

"sudo chmod 777 folderName"

Important
=============================================
* apt-fast modded from vivid to work on wily.
* You can crash your system. It hasn't been tested 100% yet. Give feedback!
* The desktop environment recommended tested right now is to use MATE desktop.
* Be careful with unstables repos, comment them if you want.
* If there are connectivity problems select your best server on Software & Updates!
* If you want to know more, go to the wiki of this repo [here](https://github.com/adgellida/ubuntupackages/wiki).

TO DO
=============================================
* Create app and integrate selectable boxes.

Release notes
=============================================
You can check it [here](https://github.com/adgellida/ubuntupackages/releases)
