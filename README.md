# .dotfiles

'''sudo pacman -S xorg-server xorg-xinit xorg-xsetroot'''

'''cp /etc/X11/xinit/xinitrc .xinitrc'''

Editar .xinitrc:

'''
# Keyboard Layout
setxkbmap -variant colemak &

# Compositor
picom -f &

# Execute DWM
exec dwm
'''
