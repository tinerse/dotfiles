# dotfiles
To install the dotfiles to your Fedora Sway you will need to make sure you have these packages

1. sudo dnf install waybar swaylock alacritty fastfetch rofi
2. To install swaync you will need to follow the steps here - https://github.com/ErikReider/SwayNotificationCenter
3. Once everything is installed download this repo and move it to your .config folder
4. To make SDDM use the right theme move the .config/sddm/ folder to Downloads/ and run these commands.
5. sudo mv /home/tinerse/Downloads/catppuccin-mocha/ /usr/share/sddm/themes/
6. sudo rm -rf /lib/sddm/sddm.conf.d/
7. sudo mv /home/tinerse/Downloads/sddm.conf.d/ /lib/sddm/
8. Now all you will need to do is edit your .config/sway/config file to match what your device uses and it should be good!
