# Kargos Script For Optimus-Manager
Kde Plasma Widget for Optimus-Manager, using [Kargos API](https://github.com/lipido/kargos).

I fork from url https://github.com/inzar98/optimus-manager-argos and I edit scrpit for Kargos Thank inzar98!

Screenshot from Kargos i adjust width 300 and height 200
![NVidia Prime Kargos Indicator](https://github.com/inzar98/optimus-manager-argos/blob/master/screenshots/optimus-manager-2.png)                                       

#### Requirements
- [Kargos](https://store.kde.org/p/1173112/) Kde Plasma Widget.
- [Optimus-Manager](https://github.com/Askannz/optimus-manager) Awesome Optimus Switch script!
- Any Arch based distro.

#### Installation
Install [Kargos](https://store.kde.org/p/1173112/) Kde Plasma Widget.

Then:
```
git clone https://github.com/lotspecter/optimus-manager-argos
cd argos-indicator-nvidia-prime

# copy icons
cp -v icons/* ~/.local/share/icons/

# copy 'optimus-manager-ar.sh' to 'argos' folder
cp -v optimus-manager-ar.sh ~/.config/argos/

# Thats All !
```
#### Uninstall
```
# remove icons
rm ~/.local/share/icons-to-delete/{nvidia-active-symbolic.svg,nvidia-inactive-symbolic.svg,prime-indicator-intel.svg,prime-indicator-intel-symbolic.svg,prime-indicator-nvidia.svg}


# remove argos extension script
rm ~/.config/argos/optimus-manager-ar.sh



