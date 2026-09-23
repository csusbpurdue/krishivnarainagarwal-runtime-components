# Runtime Components

Dotfiles and Git/shell/editor config I reuse across machines.

This repo stores the runtime files I want on a new server, laptop, or internship machine so I do not have to set bash, zsh, vim, gdb, and git up from scratch every time.

## Contents

| File | Purpose |
| --- | --- |
| `.bashrc` | Settings loaded by bash on each new terminal |
| `.zshrc` | Settings loaded by zsh on each new terminal |
| `.vimrc` | Settings loaded by vim on startup |
| `.gdbinit` | Settings loaded by gdb on startup |
| `.gitconfig` | Global git config (name, email, default branch, editor, pull behavior) |
| `install.sh` | Copies the files above into the home directory |

