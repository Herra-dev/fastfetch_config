# [fastfetch_config](https://github.com/Herra-dev/binary_)
## by [Herra-dev](https://github.com)


![Fastfetch](fastfetch/img/archlinux)

## Image used
![Fastfetch](fastfetch/img/archlinux1) can be found [here](https://github.com/Herra-dev/Herra-dev-applications-pics/fastfetch/archlinux) with a great resolution

## How to use it
### 1- Install [fastfetch](https://github.com/fastfetch-cli/fastfetch) for linux (all command must be run as sudo, doas or sup)
#### Debian / Debian based:
    apt install fastfetch
#### ArchLinux / Arch based:
    pacman -S fastfetch
#### Fedora:
    dnf install fastfetch
#### Gentoo:
    emerge --ask app-misc/fastfetch
#### Alpine:
    apk add --upgrade fastfetch
#### NixOS:
    nix-shell -p fastfetch
#### OpenSUSE:
    zypper install fastfetch
#### ALT Linux:
    apt-get install fastfetch
#### Exherbo:
    cave resolve --execute app-misc/fastfetch
#### Solus:
    eopkg install fastfetch
#### Slackware:
    sbopkg -i fastfetch
#### Void Linux:
    xbps-install fastfetch
#### Venom Linux:
    scratch install fastfetch
### 2- Generate fastfetch config:
    fastfetch --gen-config
#### or
    fastfetch --gen-config-full

### 3- Download [this](https://github.com/Herra-dev/Herra-dev-applications-pics/blob/main/fastfetch/archlinux) fastfetch config and move it into ~/.config/fastfetch/ (replace the existing config)

### 4- Download [this photo](https://github.com/Herra-dev/Herra-dev-applications-pics/fastfetch/archlinux) if you want it, or copy your own photo into diretory /home/yourUserName/.config/fastfetch/, after that, modify the path in config.jsonc file to match the path to your picture

## NOTE: [this](https://github.com/Herra-dev/Fastfetch_repo/fastfetch/config.jsonc) config was tested with [kitty](https://github.com/kovidgoyal/kitty) terminal

### see man [fastfetch](https://github.com/fastfetch-cli/fastfetch) for more information
# Thank you