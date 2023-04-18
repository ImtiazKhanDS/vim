# Vim learning

## Normal Model
- dot operator : Repeats the last action
- x : changes a character
- dd : deletes a entire line
- >G : Indents from the cursor to the bottom of the file.
- $ : Goes to the end of the line
- a : appends in the next to cursor position
- A : appends in the end of the line where cursor is present (equivalent to $a)
- s : deletes the character on the cursor and enters insert mode
- f : find the next character specified after f , for example f+ , finds + symbol forward direction
- F : find the previous character specified after F, for examples F+ finds + symbol backward.
- ; : finds the next character with the same search symbol , in the above example +
- , : finds the previous match.
- / pattern : matches the regex pattern provided , press n for next match , N for previous match.
- :s/target/replacement : substitutes the target with replacement , next target/replacement with &
- * : When the cursor is at the start of a word we can search the next occurence by pressing *
- cw: change the entire word , by deleting and writing in insert mode.
- %s:/target/replacement/g : replaces all the targets with replacements
- db: deletes letter to the beginning of the word except the beginning letter.
- dw : deletes the whole word starting from the first letter.
- daw : delete a word (most efficient one)
- ctrl+a : if cursor present on a number increments by 1
- 100 ctrl+a: increments by 100
- ctrl+x: if cursor present on a number decrements by 1
- 100 ctrl+x: if cursor present on a number decrements by 100
- 3dw: deletes three words
- d : delete a character
- y : yank into a register
- g~: swap case
- gu: smaller case
- gU : upper case
- SHIFT+>: shift to right
- SHIFT+<: shift to left
- =: Auto indent
- gUaw : makes the current word capital
- gUap : makes the whole paragraph capital
- >>: indents the current line
- <<: indents back
- gUU : changes the case of the entire line to capital
- gg=G: Auto indent the whole file.

## Insert Mode
ctrl h : Delete one character back
ctrl w : Delete back one word
ctrl u : Delete back start of the line.
yt, : yanks the word till ,
ctrl r + 0 : pastes the yanked text from register in insert mode.
ctrl r + = : opens a bottom where we can do calculation after that press enter
ctrl v + (any ascii code) : gives the letter for example ctrl v 065 => A



