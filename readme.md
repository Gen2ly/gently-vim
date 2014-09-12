### Description

A **through** vim configuration file, it is meant to replace the local `~/.vimrc`.  Built from the Vim's `vimrc_example` and various others, it has support-for:

* Basic expected functionality
* Backups, undos
* Two space indents
* Syntax highlighting, 256 color support
* Wildmenu
* Restore cursor position
* (F3) Paste toggle 
* (F5) Spell check toggle
* (Enter) Newline 
* (Space) Un-highlight search

### Usage

For Arch Linux, replace `runtime! archlinux.vim` with `runtime! gently.vim` in `/etc/vimrc`.