# Darkplus

A dark Neovim theme written in Lua ported from [Visual Studio Code](https://code.visualstudio.com/) Dark+ theme.

## Screenshots

![darkplus](https://user-images.githubusercontent.com/70239736/138616095-e7a5c2e6-5fa2-4e30-80ea-b9f0760f9da2.png)

![darkplus2](https://user-images.githubusercontent.com/70239736/138616104-91d40d45-61d3-4ce9-bc8d-6e575b7d7a46.png)

## Plugin Support

- [TreeSitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [LSP Diagnostics](https://neovim.io/doc/user/lsp.html)
- [Git Signs](https://github.com/lewis6991/gitsigns.nvim)
- [Git Gutter](https://github.com/airblade/vim-gitgutter)
- [Neogit](https://github.com/TimUntersberger/neogit)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- [NvimTree](https://github.com/kyazdani42/nvim-tree.lua)
- [Indent Blankline](https://github.com/lukas-reineke/indent-blankline.nvim)
- [Dashboard](https://github.com/glepnir/dashboard-nvim)
- [BufferLine](https://github.com/akinsho/nvim-bufferline.lua)
- [Barbar](https://github.com/romgrk/barbar.nvim)

## ⚡️ Requirements

- Neovim >= 0.5.0

## 📦 Installation

Install the theme with your preferred package manager:

[vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'martinsione/darkplus.nvim'
```

[packer](https://github.com/wbthomason/packer.nvim)

```lua
use 'martinsione/darkplus.nvim'
```

## 🚀 Usage

Enable the colorscheme:

```vim
" Vim Script
colorscheme darkplus
```

```lua
-- Lua
vim.cmd[[colorscheme darkplus]]
```

## 🔥 Contributing

If you would like to add support to a plugin or to fix a bug please feel free to send a PR.

## 💐 Credits

- [tokyonight](https://github.com/folke/tokyonight.nvim) - Readme organization and some highlight groups are heavily inspired by this plugin.

- [LunarVimColorschemes](https://github.com/LunarVim/Colorschemes) - The motivation to make this colorscheme came from this plugin,

  really cool but it had many colorschemes I didn't want. I also added some highlight groups and IMO made a better folder structure.
