# NOBLE NUMBAT

## AIM
* A guide on how to set up new `linux distros`  
* Showing how to install the `OS` and how to install  some apps

## OS INSTALLATION
- Prerequisites : `flash drive`, `laptop`
* First you need to download the `.iso` file of the `distro` you want to install
* Next you erase the flash drive
* Go to `startup disc creator` select the flash drive and the `.iso` file
* Then burn the `.iso` file to the `drive` 
* Power off your `PC` then boot it with the `drive` inserted
* Press the `esc` while booting to ascess the `BIOS`
* Select the `drive` then boot
* Choose whether you want to perform a full installation or dualboot

## APP INSTALLATION
* The app you need will be `chrome`, `VS-code`, `LAMPP`, maybe `spotify`

### CHROME
* Download the `.deb` file from [Google](https://www.google.com/chrome/)
* Then run `sudo apt update && sudo apt upgrade && sudo dpkg -i filename.deb` .

### VS-CODE
* Download the `.deb` file from [vscode](https://code.visualstudio.com/download)
* Then run `sudo apt update && sudo apt upgrade && sudo dpkg -i filename.deb` .

### SPOTIFY
* ee go far, and it changes regularly
* So just read their [Documentation](https://www.spotify.com/ng/download/linux/)

### LAMPP
* First download the `lampp` installer (`.run` file) from [Apache Friends](https://sourceforge.net/projects/xampp/)
* Then run `chmod +X filename.run && sudo ./filename.run && sudo /opt/lampp/lampp start`

## CUSTOM COMMANDS
- You can add custom commands using 2 methods 
- `Alias` & `Executable files`

### ALIAS
* First run `cd && nano ~/.bashrc`
* In the `nano` editor navigate to other alias
* then add yours `alias xamppstart='sudo /opt/lampp/lampp start'` , `alias cl='clear'`
* recall that in `nano` editor `CTRL O` will save the changes and `CTRL X` to close the editor
* Finally run `source ~/.bashrc` to refresh the commands
* Check `.bashrc` for some of my custom commands

### EXECUTABLE FILES
* first run `cd && nano ~/custom`
* check `.custom` for an example
* then make the file executable by running `chmod +x ~/custom`
* then run `sudo mv ~/custom /usr/local/bin/custom` 
* To use your command just run `custom msg1`


## DISCLAIMER 
* If your PC crashes or you lose your files na you sabi oo, backup if needed