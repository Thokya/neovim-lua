# Neovim Configuration

This is my personal NeoVom configuration in Lua. I use it on daily basis for all my coding needs, and I have configured it to my liking with a number of plugins that enhance my overall NeoVim experience.

## Plugins Used
* [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig): A built-in language server protocol (LSP) client that provides code completion, syntax highlighting, and more.
* [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter): A parsing system for syntax highlighting, code analysis, and more.
* [rose-pine theme for neovim](https://github.com/rose-pine/neovim): A beautiful color scheme for NeoVim tha includes both a light and dark vairant.
* [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim): A powerful file finder and picker that allows you to quickly search for files, buffers and more.
* [vim-fugitive](https://github.com/tpope/vim-fugitive): A Git wrapper so awesome, it should be illegal.
* [nvim-cmp](https://github.com/hrsh7th/nvim-cmp): A completion plugin for neovim coded in Lua.
* [theprimeagen-harpoon](https://github.com/ThePrimeagen/harpoon): A navigation system that allows you to easily switch between files and directories in NeoVim.

## Installation
### To install this configuration on your own machine, follow these steps
1. Clone this repository to your local machine using `git clone`.
2. Install NeoVim if you haven't already done so.
3 . Install the `packer` plugin manager by running `git clone https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim/`.
4. Open NeoVim and run `:PackerSync` to instll all plugins

# Usage
To use this configuration, simply copy the `init.lua` file to your NeoVim configuration directory. By default, this is located at `~/.config/nvim`.

# Conclusion
I hope you find it useful too. If you have any questions or suggestions, feel free to open an issue on this repository.
