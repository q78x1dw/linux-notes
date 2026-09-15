# Movements

- `w` next begin
- `b` begin
- `e` end

`word`: ends at a non-word character
`WORD`: ends at *white space*   `W` `B` `E`

- `$`
- `0`
- `^` : first non-blank character *count has no effect*

## Move to a char

`f` single-char search : `fc` goto next `c`
    accepts counts  
`F` backwards

`t` like fx but stops one char before the searched char. "To"  
`T` backwards

## match parentheses
`%`

## goto

- `[line_num]G` : goto line_num ==`:[line_num]`
- `G`
- `gg` == `1G`
- `xx%` goto xx% of the file (percent) e.g.`50%` == half

- `H` : high, top of the page(visible area)
- `M` : middle of the page
- `L` : low, last line of the page

## where is me

- `<C-G>`

## scroll

|   Step    |   Up  |   Down    |
|-----------|-------|-----------|
|1/2  screen|Ctrl-U | Ctrl-D    |
|1 line     |Ctrl-E | Ctrl-Y    |
|1 Screen   |Ctrl-F | Ctrl-B    |

- `zz` center active row


