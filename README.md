# Vim Exercises Repository

This repository contains a series of exercises and resources for learning and practicing Vim, the powerful text editor. Below are the links to the key resources available in this repository.

## Basic Commands

- `:q` - Quit NeoVim
- `:w` - Save the current file
- `:wq` or `:x` - Save and quit
- `:q!` - Quit without saving
- `:e {file}` - Open a file

## Navigation

- `h` - Move left
- `j` - Move down
- `k` - Move up
- `l` - Move right
- `gg` - Go to the top of the file
- `G` - Go to the bottom of the file
- `{line_number}G` - Go to the specified line number

## Editing

- `i` - Enter insert mode
- `a` - Enter insert mode after the current character
- `o` - Open a new line below the current line and enter insert mode
- `O` - Open a new line above the current line and enter insert mode
- `Esc` - Exit insert mode
- `u` - Undo
- `Ctrl + r` - Redo
- `dd` - Delete a line
- `yy` - Yank (copy) a line
- `p` - Paste below the cursor
- `P` - Paste above the cursor

## Visual Mode

- `v` - Start visual mode (character selection)
- `V` - Start visual line mode (line selection)
- `Ctrl + v` - Start visual block mode (block selection)

## Searching

- `/` - Search for a pattern
- `n` - Move to the next occurrence
- `N` - Move to the previous occurrence
- `:%s/old/new/g` - Replace all occurrences of 'old' with 'new' in the file

## Splitting Windows

- `:split` or `:sp` - Horizontal split
- `:vsplit` or `:vsp` - Vertical split
- `Ctrl + w w` - Switch between splits

## Tabs

- `:tabnew` or `:tabnew {file}` - Open a new tab
- `gt` - Move to the next tab
- `gT` - Move to the previous tab
- `:tabclose` - Close the current tab

## Buffers

- `:ls` - List all open buffers
- `:b {buffer_number}` - Switch to a buffer
- `:bd` - Delete a buffer (close a file)

## Plugins and Configuration

- `:PlugInstall` - Install plugins (assuming you are using vim-plug)
- `:PlugUpdate` - Update plugins
- `:source %` - Reload the current configuration file

## Custom Commands

- `:map` - Create a custom shortcut
- `:autocmd` - Define an automatic command on certain events

This list covers many of the fundamental and intermediate features of NeoVim. Explore the `:help` command in NeoVim for detailed documentation on these and other features.

## Visual Representation

![Vim Cheat Sheet (Graphical)](./cheatsheets/vim-cheat-sheet-graphical.png)
