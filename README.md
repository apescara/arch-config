# Personal config for ARCH

Set alias [Dotfiles](https://wiki.archlinux.org/title/Dotfiles)

```bash
$ git init --bare ~/.dotfiles
$ alias dotfiles='/usr/bin/git --git-dir="$HOME/.dotfiles/" --work-tree="$HOME"'
$ dotfiles config status.showUntrackedFiles no
```

Add yay
```bash
pacman -S --needed git base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```
