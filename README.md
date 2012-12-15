# The Vim Configuration of Champions

[See vimfiles's Stats on GitEgo](http://gitego.com/luan/vimfiles)

## Installation

1. `git clone http://github.com/luan/vimfiles.git` in your home folder.
2. `mv vimfiles .vim`
3. `cd .vim`
4. `rake vim:link` to make the .vimrc symbolic link.
5. Install [Vundle](https://github.com/gmarik/vundle) with `git clone http://github.com/gmarik/vundle.git bundle/vundle`
6. Run Vim and type `:BundleInstall` to install the plugins with Vundle.
7. Enjoy enhanced productivity, increased levitation, reduced watermelon-related accidents, and startling sex appeal.

## Screenshots

**MacVim** / **Windows gVim**

[![MacVim](https://github.com/luan/vimfiles/raw/master/screenshots/MacVim1_small.png)](https://github.com/luan/vimfiles/raw/master/screenshots/MacVim1.png) [![Windows gVim](https://github.com/luan/vimfiles/raw/master/screenshots/Windows1_small.png)](https://github.com/luan/vimfiles/raw/master/screenshots/Windows1.png)

## Notes

Be sure to always edit the vimrc using `,vi`, which opens the vimrc in the .vim folder. Vim has a nasty habit of overriding symlinks.

## Plugin Installation / Requirements

I may make this more verbose later, but for now, here's a list of plugins that require further installation:

 * [Command-T](https://github.com/wincent/Command-T) Needs compilation.
 * [Fugitive](https://github.com/tpope/vim-fugitive) Requires Git to be installed.
 * [ack.vim](https://github.com/mileszs/ack.vim) Requires [ack](http://betterthangrep.com/) to be installed.

## Plugin List

_Note: Auto generated by `rake plugins:update_readme`_


 * [vundle](https://github.com/gmarik/vundle) - Vundle, the plug-in manager for Vim
 * [Command-T](https://github.com/wincent/Command-T) - Mirror of the official Command-T repository at git.wincent.com
 * [vim-easymotion](https://github.com/Lokaltog/vim-easymotion) - Vim motions on speed!
 * [nerdtree](https://github.com/scrooloose/nerdtree) - A tree explorer plugin for vim.
 * [vim-powerline](https://github.com/Lokaltog/vim-powerline) - The ultimate vim statusline utility.
 * [vim-tomorrow-theme](https://github.com/chriskempson/vim-tomorrow-theme) - Tomorrow Theme for Vim
 * [vim-colors-solarized](https://github.com/altercation/vim-colors-solarized) - precision colorscheme for the vim text editor
 * [vim-commentary](https://github.com/tpope/vim-commentary) - commentary.vim: comment stuff out
 * [vim-surround](https://github.com/tpope/vim-surround) - surround.vim: quoting/parenthesizing made simple
 * [vim-fugitive](https://github.com/tpope/vim-fugitive) - fugitive.vim: a Git wrapper so awesome, it should be illegal
 * [vim-abolish](https://github.com/tpope/vim-abolish) - abolish.vim: easily search for, substitute, and abbreviate multiple variants of a word
 * [vim-eunuch](https://github.com/tpope/vim-eunuch) - eunuch.vim: helpers for UNIX
 * [tabular](https://github.com/godlygeek/tabular) - Vim script for text filtering and alignment
 * [ack.vim](https://github.com/mileszs/ack.vim) - Vim plugin for the Perl module / CLI script 'ack'
 * [vim-togglelist](https://github.com/milkypostman/vim-togglelist) - Functions to toggle the [Location List] and the [Quickfix List] windows.
 * [vim-endwise](https://github.com/tpope/vim-endwise) - endwise.vim: wisely add "end" in ruby, endfunction/endif/more in vim script, etc
 * [supertab](https://github.com/ervandew/supertab) - Perform all your vim insert mode completions with Tab
 * [MatchTag](https://github.com/gregsexton/MatchTag) - Vim's MatchParen for HTML tags
 * [neocomplcache](https://github.com/Shougo/neocomplcache) - Ultimate auto-completion system for Vim.
 * [vim-repeat](https://github.com/tpope/vim-repeat) - repeat.vim: enable repeating supported plugin maps with "."
 * [vim-matchit](https://github.com/Spaceghost/vim-matchit) - A simple mirror of vim-matchit from @mirell
 * [vim-textobj-user](https://github.com/kana/vim-textobj-user) - Vim plugin: Support for user-defined text objects
 * [vim-textobj-rubyblock](https://github.com/nelstrom/vim-textobj-rubyblock) - A custom text object for selecting ruby blocks.
 * [snipmate-snippets](https://github.com/honza/snipmate-snippets) - vim-snipmate default snippets
 * [vim-snipmate](https://github.com/garbas/vim-snipmate) - snipMate.vim aims to be a concise vim script that implements some of TextMate's snippets features in Vim. 
 * [vim-ruby](https://github.com/vim-ruby/vim-ruby) - Vim/Ruby Configuration Files
 * [vim-haml](https://github.com/tpope/vim-haml) - Vim runtime files for Haml, Sass, and SCSS
 * [vim-rails](https://github.com/tpope/vim-rails) - rails.vim: Ruby on Rails power tools
 * [vim-rake](https://github.com/tpope/vim-rake) - rake.vim: it's like rails.vim without the rails
 * [vim-rvm](https://github.com/tpope/vim-rvm) - rvm.vim: Switch Ruby versions from inside Vim
 * [vim-ruby-refactoring](https://github.com/ecomba/vim-ruby-refactoring) - Refactoring tool for Ruby in vim!
 * [vim-haml](https://github.com/tpope/vim-haml) - Vim runtime files for Haml, Sass, and SCSS
 * [vim-handlebars](https://github.com/nono/vim-handlebars) - Vim plugin for Handlebars
 * [html5.vim](https://github.com/othree/html5.vim) - HTML5 omnicomplete and syntax
 * [indenthtml.vim](https://github.com/vim-scripts/indenthtml.vim) - alternative html indent script
 * [vim-javascript](https://github.com/pangloss/vim-javascript) - Vastly improved vim's javascript indentation.
 * [jacinto.vim](https://github.com/alfredodeza/jacinto.vim) - Format and validate JSON files
 * [vim-coffee-script](https://github.com/kchmck/vim-coffee-script) - CoffeeScript support for vim
 * [jasmine.vim](https://github.com/luan/jasmine.vim) - Jasmine Plugin for Vim
 * [vim-css3-syntax](https://github.com/mutewinter/vim-css3-syntax) - Add CSS3 syntax support to vim's built-in `syntax/css.vim`.
 * [vim-markdown](https://github.com/hallison/vim-markdown) - Markdown syntax highlight for Vim editor with snippets support
 * [L9](https://github.com/vim-scripts/L9) - Vim-script library
 * [vim-addon-mw-utils](https://github.com/MarcWeber/vim-addon-mw-utils) - vim: interpret a file by function and cache file automatically
 * [tlib_vim](https://github.com/tomtom/tlib_vim) - Some utility functions for VIM

_That's 44 plugins._
