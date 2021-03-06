### Description

A thorough Vim configuration file meant to replace the local `~/.vimrc`.  Built from the Vim's `vimrc_example` and various others, it has support-for:

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

Replace `runtime! archlinux.vim` with `runtime! gently.vim` in `/etc/vimrc` to enable.

The configuration directs Vim to use the XDG user directories.  Create their directories by doing:

```bash
mkdir -p ~/.cache/vim/backup/
mkdir -p ~/.config/vim/
mkdir -p ~/.local/share/vim/{after,colors,plugin,syntax}
```

