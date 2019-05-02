Forked from [vim-scripts/grep.vim](https://github.com/vim-scripts/grep.vim)

# Overview

The grep plugin integrates the grep, fgrep, egrep, and agrep tools with
Vim and allows you to search for a pattern in one or more files and jump
to them.

To use this plugin, you need the grep, fgrep, egrep, agrep, find and
xargs utilities. These tools are present in most of the Unix installations.
For MS-Windows systems, you can download the GNU grep and find utilities
from the following sites:

   http://gnuwin32.sourceforge.net/packages/grep.htm
   http://gnuwin32.sourceforge.net/packages/findutils.htm


# New Feature

![](https://raw.githubusercontent.com/whatsrtos/grep.vim/master/screenshot/VimGrepStr.png)


1. Add a new vim command `:VimGrepStr` : open a window to set grep options, like [EasyGrep](https://github.com/dkprice/vim-easygrep) ;
2. Support async job control api for vim8+ ;


# Usage

* `:VimGrepStr`, You can map a key to invoke any of the command: `nnoremap <silent> <F3> :VimGrepStr<CR>`


# ToDo

* Support `ack`, `ag` ;
* Support replace ;
