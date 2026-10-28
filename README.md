# bytefetch

The worlds smallest fetch tool*, written as a shell script with no dependencies.

*It is the smallest **dependency free**  script (for the amount of information is collects) . It is 721 bytes, which is smaller than this readme.
(I have yet to find any fetch tools smaller than mine) 
```
    .--.     user@arch
   |o_o |    os     Arch Linux
   |:_/ |    kernel 6.17.2-arch1-1
  //   \ \   uptime 5d 21h 4m
 (|     | )  pkgs   1344
/'\_   _/`\  shell  bash
\___)=(___/  de     Hyprland
             term   kitty
             cpu    AMD Ryzen 5 7535HS with Radeon Graphics
             memory 7651/31387 MiB
```
## Why would you use this?
Most fetch tools call uname, awk or grep. This one is different since it only reads files the kernel already provides.
## install

    install -Dm755 bytefetch ~/.local/bin/bytefetch

## notes
- Linux only
- Package counts work with pacman, dpkg, xbps and portage.
- Loads in ~2 ms (fastfetch usually takes around 4ms)

