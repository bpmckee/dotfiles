# Dotfiles
These are the dotfiles I use on my personal computers.  They're managed using [Stow](https://www.gnu.org/software/stow/).

## Requirements
Install [Stow](https://www.gnu.org/software/stow/).

* Arch - Get it from the AUR
* Debian `sudo apt-get install git stow`
* OSX `brew install stow`

Other requirements

- Install NeoVim
- Install Vim plug, then run :PlugInstall
- Install Zsh
- Install zplug
- Install tmux
- Install Hack Nerd Font

## Usage

1. Clone the repo. `cd ~ && git clone https://github.com/bpmckee/dotfiles.git .dotfiles && cd .dotfiles`
2. Update the submodules `git submodule init && git submodule update`
3. Apply the dotfiles you care about `stow -v alacritty`

