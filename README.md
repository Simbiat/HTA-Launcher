# HTA-Launcher
Sometimes you may need to provide easy access to a set of scripts (batch files). You can always give access to a folder where .cmd and .bat files lie, but this will require to provide access to each file separately or to all of them at once. In some cases it's better to use a simple GUI like this (screenshot taken in 4K with scaling and does not represent real look):
![alt UI sample](https://raw.githubusercontent.com/Simbiat/HTA-Launcher/master/launchmain.png)

This is an HTA file (Visual Basic Script with HTML), To correctly work it will also require a configuration file like this (domain before username is mandatory).

You set up user access in the configuration file and add the scripts in HTA file itself. For security purposes this HTA file uses Validata's hashfile.exe to validate hash of each script before running it. "Golden" hash is to be placed in HTA file.

All actions are logged into a logfile which can be viewed through this HTA like this (screenshot taken in 4K with scaling and does not represent real look; username is reducted): ![alt Logs sample](https://raw.githubusercontent.com/Simbiat/HTA-Launcher/master/luancherlogs.png)

Some of the functions used here are also described in separate repositories.
