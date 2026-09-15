# Vim user manual -- Basics

make help bars visible:
```vim
:set concellevel=0
:hi link HelpBar Normal
:hi link HelpStar Normal
```


## Basic Edits

- Delete Line Break:
    `J` at the first line joins the 2nd line.

- Redo `<C-r>` instead of `r`
- `U` is a change by itself. *so could be <C-r>ed*

- `a`inserts **AFTER** current cursor and `i` is **BEFORE**

- `ZZ` == `:wq`

## help

- `:help deleting`
- `:help x`             : normal mode
- `:help CTRL-r`
- `:help -t`
- `:help 'number' `     : Options
- `:help E37`           : Error Message
- `Ctrl-D`              : show a list of possibilities , help topic.
- 

### prefixes

- `:help i_CTRL-H`      : insert mode *prefix*
- `v_o` visual mode
- `c_%` command line
- `:s` Ex-commands
- `/` e.g. `/\+` : regexp items
- `CTRL-W_p`            : windows 
- `quote:` : register `:`

### special txts
- `:help vimeval.txt`   : vimscript
- `:help index`         : *index of all commands*
- `:help pattern.txt`   : regex
- `:help function-list`
- `:help windows.txt`

- `:help lua.txt` `help lua-guide.txt` `help lua-ref.txt`
