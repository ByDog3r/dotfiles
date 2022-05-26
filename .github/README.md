## Dotfiles & Configs

![Screenshot1](https://user-images.githubusercontent.com/66902449/169684508-c6da8180-69a0-4835-90a6-1f51385ec064.png)
![Screenshot2](https://user-images.githubusercontent.com/66902449/169684529-6890cbc0-3e3a-44e4-a580-8ccb80497f90.png)
![Screenshot3](https://user-images.githubusercontent.com/66902449/169684557-89590758-72b8-4cf2-adde-59e5f1bed282.png)


<h1>
  <a href="#--------">
    <img alt="" align="left" src="https://img.shields.io/github/stars/bydog3r/dotfiles?color=162026&labelColor=162026&style=for-the-badge"/>
  </a>
  <a href="#--------">
    <img alt="" align="right" src="https://badges.pufler.dev/visits/bydog3r/dotfiles?style=for-the-badge&color=162026&logoColor=white&labelColor=162026"/>
  </a>
</h1>

## Install this dotfiles
[Read dotfiles wiki](https://github.com/ByDog3r/dotfiles/wiki/INDEX-OF) to install for manual way.

```bash
# Clone dotfiles.
git clone https://github.com/ByDog3r/dotfiles.git

# Copy my configs
cp -r .config/* ~/.config/

# Copy my .xprofile and .zshrc configs
cp .profile .zshrc ~/

# Sample to install my apps
sudo pacman -S wine

# Set your wallpaper, edit .xprofile and find this line
feh --bg-scale Pictures/bg.png &

# Set your qtile theme, edit .config/qtile/settings/theme.py 
# and find this line:

def load_theme():
    theme = "rosepine"
    ...
```

## Details

Below is a list of some of the packages that I use for my current setup.

- **Operating System** --- [Archlinux](https://www.archlinux.org/)
- **AUR Helper** --- [Paru](https://aur.archlinux.org/packages/paru-git/)
- **Pentesting repositories** --- [BlackArch](https://blackarch.org/strap.sh)
- **Boot Loader** --- [Grub](https://wiki.archlinux.org/index.php/GRUB)
- **Window Manager** --- [Qtile](https://aur.archlinux.org/packages/qtile-git)
- **Screen Locker** --- [Betterlockscreen](https://aur.archlinux.org/packages/betterlockscreen)
- **Shell** --- [ZSH](https://www.zsh.org)
- **Terminal** --- [Kitty](https://wiki.archlinux.org/index.php/Kitty)
- **Compositor** --- [Picom](https://wiki.archlinux.org/index.php/Picom)
- **Notification Daemon** --- [Dunst](https://wiki.archlinux.org/index.php/Dunst)
- **Application Launcher** --- [Rofi](https://wiki.archlinux.org/index.php/Rofi)
- **File Manager** --- [Ranger](https://aur.archlinux.org/packages/ranger-git) & [Thunar](https://docs.xfce.org/xfce/thunar/start)
- **Editor** --- [Neovim](https://aur.archlinux.org/packages/neovim-git)
  - **Plugins**
	- [NvChad](https://nvchad.github.io)
- **Web Browser** --- [Opera](https://www.opera.com)
- **PDF Viewer** --- [Okular](https://okular.kde.org)
- **Video player** --- [Mpv](https://aur.archlinux.org/packages/mpv-git)
- **Screen Recorder** -- [SimpleScreenRecorder](https://www.maartenbaert.be/simplescreenrecorder/)
- **Run Windows applications** -- [Wine](https://www.winehq.org)

## Keybindings
I use <kbd>mod/super</kbd> AKA Windows key as my main modifier.
also with <kbd>alt, shift, and ctrl</kbd>

<details>
<summary><b>Window Manager</b></summary>

| Keys                                 | Action                         |
| ------------------------------------ | ------------------------------ |
| <kbd>MOD + j</kbd>                   | Next windown (down)            |
| <kbd>MOD + k</kbd>                   | Next windown (up)              |
| <kbd>MOD + TAB</kbd>                 | Change layout                  |
| <kbd>CTRL + MOD + r</kbd>            | restart Qtile                  |
| <kbd>CTRL + MOD + q</kbd>            | shutdown Qtile                 |
| <kbd>MOD + w</kbd>                   | kill window                    |
| <kbd>MOD + RETURN</kbd>              | spawn terminal                 |
| <kbd>MOD + Print</kbd>               | Screenshot                     |
| <kbd>MOD + [1-7]</kbd>               | Switch to workspace N (1-7)    |
| <kbd>MOD + SHIFT + [1-7]</kbd>       | Send window to workspace (1-7) |

</details>

<details>
<summary><b>Application</b></summary>
	
| keys                                 | Action                    |
|--------------------------------------|---------------------------|
| <kbd>MOD + m</kbd>                   | Rofi Menu                 |
| <kbd>MOD + SHIFT + m</kbd>           | Nav Menu                  |
| <kbd>MOD + b</kbd>                   | Run Opera                 |
| <kbd>MOD + e</kbd>                   | Run Thunar                |
| <kbd>MOD + r</kbd>                   | Run Redshift              |
| <kbd>MOD + SHIFT + r</kbd>           | Stop Redshift             |
</details>

## Terminal Commands

<details>
<summary><b>ZSH Aliases</b></summary>

| Command                              | Function                    |
|--------------------------------------|-----------------------------|
| update                               | Update and upgrade os-tools |
| install                              | Paru installer              |
| clone                                | Clone repositorie           |
| hclean                               | Clean terminal history      |
| uninstall                            | Pacman and paru uninstall   |
| neofetch                             | Run neofetch config         |

</details>

<details>
<summary><b>ZSH Functions</b></summary>

| Command                              | Function                          |
|--------------------------------------|-----------------------------------|
| rmk                                  | Remove file (forense function)    |
| mkt                                  | Make pentest directorys (s4vitar) |
| extractPorts                         | Extract Ports                     |

</details>


<br>

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center"><a href="https://github.com/ByDog3r/dotfiles/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=flat-square&label=License&message=APACHE-2.0&logoColor=eceff4&logo=github&colorA=061115&colorB=67AFC1"/></a></p>
