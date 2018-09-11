# linux-resolution


```
list monitors and resolutions
xrandr

```

### Script
```
#!/bin/bash
xrandr --newmode "1920x1080_60.00"  173.00  1920 2048 2248 2576  1080 1083 1088 1120 -hsync +vsync
xrandr --addmode DVI-I-2 1920x1080_60.00
xrandr --output DVI-I-2 --mode 1920x1080_60.00


```

## Some utils commands

```
xrandr --output DVI-I-1 --auto
xrandr --output HDMI-1 --mode 1920x1080
Add resolution
cvt 1920 1080
Modeline "1920x1080_60.00"  173.00  1920 2048 2248 2576  1080 1083 1088 1120 -hsync +vsync
xrandr --newmode "1920x1080_60.00"  173.00  1920 2048 2248 2576  1080 1083 1088 1120 -hsync +vsync
xrandr --addmode DVI-I-1 1920x1080_60.00
xrandr --output DVI-I-1 --mode 1920x1080_60.00

```



## References

https://wiki.archlinux.org/index.php/xrandr

