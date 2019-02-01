vim visual studio proj

project vim for console vim.
project gvim for gui vim.

This visual studio solution aim to explore vim source code with the help of visual studio ide.

vimsrc is the original vim source directory.

project add source file according to the makefile vimsrc/src/Make_mvc.mak described in vimsrc/src/INSTALLpc.txt .

vim: https://www.vim.org/
vim github: https://github.com/vim/vim
vim-8.1.tar.bz2: ftp://ftp.vim.org/pub/vim/unix/vim-8.1.tar.bz2


devenv /DebugExe vim.exe  ; open vs prompt, type command to debug vim.exe compiled by nmake, right click vim on the left, debug--step debug, cant see the variable, but the code logic in file

same name file: on file right click, property--c/c++ -- output file--object file name-- like: $(IntDir)term_parser

