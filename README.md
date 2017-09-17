# Stripping-Pi

1. remove programs we dont need

sudo apt purge wolfram-engine bluej geany greenfoot scratch scrath2 nodejs libreoffice-* sonic-pi sense-hat minecraft-pi claws-mail claws-mail-i18n

2. Remove packages with dependencies on uninstalled programs

sudo apt-get autoremove --purge 

3. General Update

sudo apt-get update && sudo apt-get upgrade -y 
