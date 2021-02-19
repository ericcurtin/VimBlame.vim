# VimBlame.vim [![Build Status](https://travis-ci.org/ericcurtin/VimBlame.vim.svg?branch=main)](https://travis-ci.org/ericcurtin/VimBlame.vim)
Diplay git blame info in vim buffer.

## Installation
Copy `VimBlame.vim` into your ~/.vim/plugin directory.
Or `:source VimBlame.vim` to load it into your running session.

You can set a keyboard shortcut if you want by placing something like: 
```
  map <F6> :call VimBlame.vim()<CR>
```
in your `~/.vimrc` file.  Yes, the `<CR>` is literally there at the end
as the four characters shown.

### Installing with Vundle
Add `Plugin 'ericcurtin/VimBlame.vim'` to your your plugin definitions
in your `.vimrc`

