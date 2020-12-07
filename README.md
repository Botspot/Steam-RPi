# Steam-RPi
This repository hosts a template config file for box86 Steam on RPi to allow it to launch as "Small Mode" by default.  
Mainly intended for the Pi-Apps Steam App, though you could use this for an existing Steam install if you wanted to.

# To install:
After installing Steam first, you can run this command manually to change your config file to this "Small Mode" version:
```
mkdir -p ~/.local/share/Steam/config
wget https://raw.githubusercontent.com/Botspot/Steam-RPi/main/DialogConfig.vdf -O /home/pi/.local/share/Steam/config/DialogConfig.vdf
```
