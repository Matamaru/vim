# The Vim cheatsheet

---

## Playing melodies

In Normal mode, we compose commands by typing one or more keystrokes in sequence. These commands appear as follows:

| Notation | Meaning |
|:---------|:--------|
| `x`	| Press x once |
| `dw`	| In sequence, press d, then w |
| `dap` | In sequence, press d, a then p |

---

## Playing chords

Press keys in combination: 

| Notation | Meaning |
|:---------|:--------|
| `<C-p>`	| While holding down <Ctrl> press the p key. |
| `<S-a>`	| While holding down <Shift> press the a key. |


You can combine chords and melodies:

| Notation | Meaning |
|:---------|:--------|
| `<C-n>` | While holding down <Ctrl> press n |
| `g<C-]>` | Press g, then while holding down <Ctrl> press ] |
| `<C-r>0` | While holding down <Ctrl> press r, then release <Ctrl> and press 0 |
| `<C-w><C-=>` | While holding down <Ctrl> press w then = | 

---

## Special keys

| Notation | Meaning |
|:---------|:--------|
| `<Esc>` | Press the Escape key |
| `<CR>` | Press the carriage return key (also known as <Enter>) |
| `<Ctrl>` | Press the Control key (german layout <Strg>) |
| `<Tab>`	 | Press the Tab key |
| `<Shift>` | Press the Shift key |

---

## Placeholders

| Notation | Meaning |
|:---------|:--------|
| `{n}` | n = natural number, e. g. 3dd deletes the next three lines |
| `{a-z}`	 | any lower case letter |
| `{a-zA-Z}` |any lower or upper case letter |
| `{motion}` | hjkl, e.g. dh deletes the next left char form cursor position |

---

## Movement

| Notation | Meaning |
|:---------|:--------|
| `h` | Left |
| `j` | Down |
| `k` | Up |
| `l` | Right |
| `w` | jumps to the first char of the next word |
| `e` | jumps to the last char of the word |
| `b` | jumps one word back to the first char of the word |
| `)` | jumps to the first char of the next sentence |
| `(` | jumps back to the first char of the sentence |
| `{` | jumps back to previous paragraph (empty line above paragraph) |
| `}` | jumps ahead to next paragraph (empty line below paragraph) |
| `]]` | jumps to previous section |
| `[[` | jumps to next section |


---

## Modes 

| Notation | Meaning |
|:---------|:--------|
| `<Esc>` | Normal mode |
| `i` | Insert mode at cursor position |
| `:` | Command mode, internal shell |
| `v` | Visual mode |
| `<S-v>` | Visual Line mode |
| `<S-r>` | Replace mode |

---

## The Vim way 
Especially in coding, we have a lot of repetetive processes. Vim is very good with simplifying this kind of work.

| Intent | Act | Repeat | Reverse |
|--------|-----|--------|---------|
| Make a change | `{edit}` | `.` | `u` |

---

## Commands

| Notation | Meaning |
|:---------|:--------|
| `:q` | quit: exit vim |
| `:w` | write: save current file |
| `:wq` | write and quit: save current file and exit |
| `.`	| repeat last action | 
| `a `| append: insert mode behind cursor position |
| `<S-a>` | append at end of line: insert mode behind last char in line |

---

## Copy, paste, delete, cut

| Notation | Meaning |
|:---------|:--------|
| `dw` | delete word: deletes the next word |
| `{n}dw` | deletes the next n words (n = natural number) |
| `dd` | delete line |
| `{n}dd` | deletes the next n lines |
| `s` | deletes character under cursor and starts insert mode |
| `yw` | yank(=copy) word to vim buffer |
| `y{n}w` | yank the next n words |
| `yy` | yank line |
| `{n}yy` | yank the next n lines |
| `p` |	paste from vim buffer |
		
---
