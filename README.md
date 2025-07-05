# steam-big-picture-session
A gamescope session for Steam Big Picture mode straight from the display manager

## What is this?
Using [gamescope](https://github.com/ValveSoftware/gamescope) steam can be run in big picture mode directly from the display manager.

## Dependencies
* gamescope
* steam

## Installation

Since steam does not support exiting from big picture mode back to the display manager it is recommended to add a non-steam game with the parameters:
```Bash
- Name: Steam Shutdown
- Target: steam
- Launch options: -shutdown
```

### Arch Linux
Install the AUR package [steam-big-picture-session](https://aur.archlinux.org/packages/steam-big-picture-session) 
```bash
yay -S steam-big-picture-session
```

### Other 
Place the provided .desktop file in the specified location:
```bash
steam-big-picture.desktop -> /usr/share/wayland-sessions/steam-big-picture.desktop
```


