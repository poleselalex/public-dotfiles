# Public dotfiles
Dotfiles for my ArchLinux Workstation
## Dependencies
- [`i3-gaps-rounded`](https://aur.archlinux.org/packages/i3-gaps-rounded-git) 
- [`alacritty`](https://wiki.archlinux.org/title/Alacritty)
- [`dmenu`](https://wiki.archlinux.org/title/dmenu)
- [`nitrogen`](https://archlinux.org/packages/extra/x86_64/nitrogen/)

## Recommended
- [`pywal`](https://github.com/dylanaraps/pywal) (terminal color scheme)
- [`flameshot`](https://wiki.archlinux.org/title/Flameshot) (to take screenshots)

## Install
``` bash
git clone https://github.com/poleselalex/public-dotfiles.git
cp -a public-dotfiles/. ~/.config/
```

*You should edit these config files as your needs first, this is a basic configuration*

## Notes
Make sure that your `~/.config` directory exists, then it might look like this:

```
.config
├── alacritty
│   └── alacritty.yml (alacritty terminal emulator configuration)
├── i3
│   └── config (i3 config)
├── i3status
    └── config (config for i3status, i3bar)
```