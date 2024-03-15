# arch-desktop
Information and configuration files for my Arch Linux desktop installation.

## Hardware Specs
https://pcpartpicker.com/user/FloridaGuy/saved/XdjMCJ

## Packages
<details>
 <summary>A list of my explicitly installed packages (Click to expand)</summary>

  https://archlinux.org/packages/
  ### Core
   - `amd-ucode`
   - [`base`](https://archlinux.org/packages/core/any/base/) (meta package)
   - `base-devel` (meta package)
   - `btrfs-progs`
   - `linux`
   - `linux-firmware`
   - `nano`
  ### Extra
   - `ark`
   - `ffmpegthumbs`
   - `firefox`
   - `flatpak`
   - `flatpak-kcm`
   - `fwupd`
   - `git`
   - `gwenview`
   - `i2c-tools`
   - `kcolorchooser`
   - `kdegraphics-thumbnailers`
   - `kio-gdrive`
   - `libreoffice-fresh`
   - `mesa`
   - `nano-syntax-highlighting`
   - `neofetch`
   - `networkmanager`
   - `openrgb`
   - [`plasma-meta`](https://archlinux.org/packages/extra/any/plasma-meta/) (meta package)
   - `shotcut`
   - `spectacle`
   - `ufw`
   - `vulkan-radeon`
   - `xf86-video-amdgpu`
  ### Multilib
   [(Must be manually enabled)](https://wiki.archlinux.org/title/Official_repositories#Enabling_multilib)
   - `lib32-mesa`
   - `lib32-vulkan-radeon `
   - `steam`
  ### AUR
   - `mkinitcpio-firmware`
   - `paru`
   - `vesktop`
  ### Flatpak
   - `com.spotify.Client`
</details>

## Useful Stuff
<details>
 <summary>SDDM - Disable all displays except for primary on login screen (Click to expand)</summary>

  - See configuration file: `/usr/share/sddm/scripts/Xsetup`
</details>

<details>
 <summary>Firefox on KDE Plasma uses incorrect File Picker (Click to expand)</summary>
  
  - Go to `about:config` and set `widget.use-xdg-desktop-portal.file-picker` from `2` to `1`. <br />
  *(Working as of Firefox Version 123.0)* <br />
  https://wiki.archlinux.org/title/Firefox#KDE_integration
</details>
