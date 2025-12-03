# Helix notes

Mostly the changes I trip up coming from Vim.

### Selections

`x` = extend to current line, chain with next line
`X` = extend to current line

`;` = collapse to one cursor
`,` = only primary selection
`a-,` = remove primary selection

`a-;` = flip selection/anchor(?)
`a-:` = force forward sel

`a-s` = split selection on \n
`a--` = merge sels
`a-_` = merge consecutive sels

`C` = add cursor below
`a-C` = add cursor above

`a-d` = delete without yank

### Misc

```
~ = swap case
` = tolower
a-` = toupper
```

`&` = align columns

`c-c` = {un,}comment

`SPC ? %b <keybind>` = search by keybind

### AST selection
`a-i` = `a-Up`, `a-o` = `a-Down`
`a-p`, `a-n` = prev/next sibling
`a-b`, a-e` = start/end of parent
`a-a` = all siblings
`a-I` = all children

### Goto (`g`-...)

`tcb` = top/middle/bottom

### Match/surround (`m`-...)

`m` = matching (vim `%`)
`s`+char = surround sel
`r`+from+to = change surround from `from` to `to`
`d`+char = delete surround

### Spc

`f` = file picker
`F` = `cwd` file picker
`k` = hover()
`s` = document symbol picker
`S` = workspace symbol picker
`r` = rename
`a` = code_action()
`h` = references

### Jumps

`c-o` =

### `] [`

`]d [d` = next/prev diag
`]D [D` = last/first diag in file
`]f [f` = next/prev fn
`]t [t` = next/prev type
`]a [a` = next/prev arg

### `c-w`

`s` = :sp
`v` = :vsp
`HJKL` = swap with split left/below/above/right
