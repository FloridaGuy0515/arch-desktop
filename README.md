# arch-desktop
Information and configuration files for my Arch Linux desktop installation.

## Hardware Specs
https://pcpartpicker.com/user/FloridaGuy/saved/XdjMCJ

## Packages
<details>
 <summary>(Click to expand)</summary>

  https://archlinux.org/packages/
  ### Core
   - `amd-ucode`
   - [`base`](https://archlinux.org/packages/core/any/base/) (meta package)
   - `linux`
   - `linux-firmware`
  ### Extra
   - [`plasma-meta`](https://archlinux.org/packages/extra/any/plasma-meta/) (meta package)
  ### Multilib
   [(Must be manually enabled)](https://wiki.archlinux.org/title/Official_repositories#Enabling_multilib)
</details>

## Useful Stuff
<details>
 <summary>Firefox on KDE Plasma uses incorrect File Picker (Click to expand)</summary>
  
  *(Working as of Firefox Version 123.0)* <br />
  - Go to `about:config` and set `widget.use-xdg-desktop-portal.file-picker` from `2` to `1`. <br />
  https://wiki.archlinux.org/title/Firefox#KDE_integration
</details>
