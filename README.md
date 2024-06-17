# debian12
debian 12 system config/notes/build

# copy default xinit config to home dir
cp xinitrc to ~/.xinitrc

# delete all text in ~/.xinitrc and add
exec dwm

# packages to install
xorg, feh, redshift, firefox-esr, discord, obsidian

# set refresh rate
xrandr --rate 240

# set red shift
redshift -P -O 3000

# add gui audio controller
sudo apt install pavucontrol

