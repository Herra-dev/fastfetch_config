# [fastfetch_config](https://github.com/Herra-dev/binary_)
## by [Herra-dev](https://github.com/Herra-dev)


![Fastfetch](https://github.com/Herra-dev/Herra-dev-applications-pics/blob/main/fastfetch/archlinux1)

## Image used
![Fastfetch](https://github.com/Herra-dev/Herra-dev-applications-pics/blob/main/fastfetch/mini/archlinux)

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

### 3- Download [this](https://github.com/Herra-dev/fastfetch_config/blob/7e0e3fdc7835232e9020c2c631ae798093702982/fastfetch/config.jsonc) fastfetch config and move it into ~/.config/fastfetch/ (replace the existing config)

### 4- Download [this photo](https://github.com/Herra-dev/Herra-dev-applications-pics/blob/main/fastfetch/archlinux) if you want it, or copy your own photo into diretory /home/yourUserName/.config/fastfetch/, after that, modify the path in config.jsonc file to match the path to your picture

## NOTE: [this](https://github.com/Herra-dev/fastfetch_config/blob/7e0e3fdc7835232e9020c2c631ae798093702982/fastfetch/config.jsonc) config was tested with [kitty](https://github.com/kovidgoyal/kitty) terminal

### see [fastfetch](https://github.com/fastfetch-cli/fastfetch) for more information
# Thank you