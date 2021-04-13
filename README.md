# gruvbox.nvim

A port of the [Gruvbox](https://github.com/morhetz/gruvbox) colorscheme for Neovim written in lua using colorbuddy.nvim.

## Requirements

You need to be running Neovim 0.5.0+

## Installation

Install via package manager:
```vim
" If you are using Vim-Plug
Plug 'tjdevries/colorbuddy.nvim'
Plug 'taphill/gruvbox.nvim'
```

```lua
-- If you are using Packer
use 'tjdevries/colorbuddy.nvim'
use 'taphill/gruvbox.nvim'
```

Enable the colorscheme:

```vim 
" Vim-Script:
colorscheme gruvbox_nvim
```

```lua
-- Lua:
require('colorbuddy').colorscheme('gruvbox_nvim')
```

## Features

The color palette is identical to the original [Gruvbox](https://github.com/morhetz/gruvbox) and the syntax highlighting should be the same in most cases.

At this time, only dark mode is available and I don't have plans of creating a light mode or different contrast options. I also do not plan on adding plugin-specific highlighting, but that could change. If you would like to add those for yourself I would suggest forking this project.

## TODO

There are still some extended filetype highlighting options that I have not yet added for the following languages:

-  Clojure, C, PureScript, CoffeeScript, Objective-C, MoonScript, Java, Haskell, Vim, XML
