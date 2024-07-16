# nvim-config
My NeoVim config. 
I am using [NvChad](https://github.com/NvChad/NvChad) configuration.

## Dependencies
- [NeoVim](https://neovim.io/) version 0.10.0 or higher.
- [NerdFonts](https://www.nerdfonts.com/) for pretty icons in the file explorer.
- [RipGrep](https://github.com/BurntSushi/ripgrep) required by NvChad.

## Instalation
Create a symbolic link (recomended) or copy the `.config/nvim` folder into your home directory `~/.config/nvim`:
```bash
# Creating a symbolic link
$ ln -s $(PWD)/.config/nvim ~/.config/nvim
$ nvim
```
```bash
# Copy this project configuration files
$ cp -r $(PWD)/.config/nvim ~/.config/nvim
$ nvim
```
NvChad should start downloading the dependencies. After it finishes run `:MasonInstallAll` command.

