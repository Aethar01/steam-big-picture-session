# steam-big-picture-session

## What is this?
Using [gamescope](https://github.com/ValveSoftware/gamescope) steam can be run in big picture mode directly from the display manager.

## Dependencies
* gamescope
* steam

## Installation

Since steam does not support exiting from big picture mode back to the display manager it is recommended to add the .desktop file "steam-shutdown.desktop" as a non-steam game.

### Arch Linux
Install the AUR package []() 
```bash
yay -S wayland-steam-big-picture
```

### Other 
Place the provided .desktop file in the specified location:
```bash
steam-big-picture.desktop -> /usr/share/wayland-sessions/steam-big-picture.desktop
steam-shutdown.desktop -> /usr/share/applications/steam-shutdown.desktop
```


