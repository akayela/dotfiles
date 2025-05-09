# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system and ensure all necessary setup for each package

### Alacritty

```
$ sudo snap install alacritty --classic

```

### Astronvim

```
$ mv ~/.config/nvim ~/.config/nvim.bak

$ mv ~/.local/share/nvim ~/.local/share/nvim.bak
$ mv ~/.local/state/nvim ~/.local/state/nvim.bak
$ mv ~/.cache/nvim ~/.cache/nvim.bak

$ git clone --depth 1 https://github.com/AstroNvim/template ~/.config/nvim
$ rm -rf ~/.config/nvim/.git
$ nvim

```

### Oh-my-bash

```
$ bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"

```
### Git

```
$ sudo apt install git

```
### Stow

```
$ sudo apt install stow

```

### Tmux

```
$ sudo apt install tmux
$ sudo apt install tmuxinator
```

### Clone dotfiles

```
$ cd $HOME
$ git clone git@github.com:akayela/dotfiles.git

```

### Installation

To move already existing configs to dotfile and the symlink them back to the .config dir

```
$ stow .
```

### Tutorial

https://www.youtube.com/watch?v=y6XCebnB9gs
