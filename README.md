# neovim-cheatsheet

> [!NOTE]
> `<leader>` by default is `space`

---

### Search
- `/<search-term>` press enter and you can use `n` to find next occurance of search term or `N` to find previous occurance of search term
---

### Copy
- `yy` copy line, first `y` represents the start you want to copy then the second `y` represents the end you want to copy
- `:%y+` copy the entire file
- `"y+` copy to clipboard
- `v` to enter visual mode
- `V` to enter line-wise visual mode
- Place cursor on the function name, then `V`, then `/^}` and enter, `y` to yank, `p` to paste. This will copy a function.

---

### Delete
- `dd` delete line
- `ma` to mark a as starting point, `d'a` to delete to the second a as the ending point
- `{number}dd` to like delete the number of lines
- `ciw` replace word

---

### Moving the cursor
- `gg` cursor to beginning of file
- `G` cursor to end of file
- `:{line number}` or `{number}G` move cursor to specific line
- `C` move to end of line and enter insert mode
- `ggvG` highlight entire file

---

### Basic vim motions horizontally
- `w` jump to beginning of the next word
- `b` jump to beginning of the word backwords
- `e` jump to end of a word
- `ge` jump to the end of the word backwards
- `0` moves to the first character in line
- `$` moves the end of the line

> [!NOTE]
> Can use capital words `W` `B` `E` `gE` for faster movement

---

### Basic vim motions vertically
- `}` jump entire paragraphs downwards
- `{` jump entire paragraphs upwards
- `CTRL-D` move half a page down
- `CTRL-U` move half a page up
- `{number}UP` move number of lines up
- `{number}DOWN` move number of lines down
- `H` `M` `L` High Middle Low of the screen

---

### Exiting
- `:q` fails if there are any unsaved changes
- `:q!` quit without saving (force quit)
- `:wq` quit and save
- `ZZ` save and quit
- `ZQ` quit without saving
