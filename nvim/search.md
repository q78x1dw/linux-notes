# search

`/` `?`backwards

*have special meanings* `*[]^%/\?~$`

- `n` `N`

> *History* `/ ?` and `:` cmds have history

### search a word

`*` search current word (the cursor is on)  
`#` reverse

### search for whole words

- `/the\>` words that end with `the`  `\>` -> only match @ the end of a word.
- `/\<the` words that start with `the` `\<` -> only match @ the beginning of a word.
- `/\<the\>` only search `the`


## simple search patterns

- `^` beginning of a line.  
- `$` end of a line.

- `.` any single char   *reminder* escape with `\` if want to match a literal `.`

