# dotfiles
mimirot's dotfiles for MacBookAir

## Setting Up (Mac)
### clone
In order to set up with this repository on Mac, try

```bash
cd
git clone https://github.com/mimirot/dotfiles.git
```

### set symbolic link
then set symbolic links for each files and directories

#### vimrc
```bash
cd
ln -s ./dotfiles/vim/.vimrc .vimrc
```

#### neovim (and its backup directory)
```bash
cd ~/.config
ln -s ~/dotfiles/nvim nvim
ln -s ~/dotfiles/nvim.bak/ nvim.bak
```

#### kitty
```bash
cd ~/.config
ln -s ~/dotfiles/kitty kitty
```
