# Stripping-Pi
0. Change Password for pi account 

1. remove programs we dont need

sudo apt purge wolfram-engine bluej geany greenfoot scratch nodejs libreoffice sonic-pi sense-hat minecraft-pi claws-mail claws-mail-i18n python python3

2. Remove packages with dependencies on uninstalled programs

sudo apt-get autoremove --purge 

3. General Update

sudo apt-get update && sudo apt-get upgrade -y 
