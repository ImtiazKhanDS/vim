# Vim learning

## Normal Model
- dot operator : Repeats the last action
- x : changes a character
- dd : deletes a entire line
- \>G : Indents from the cursor to the bottom of the file.
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
- \* : When the cursor is at the start of a word we can search the next occurence by pressing *
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
- \>>: indents the current line
- <<: indents back
- gUU : changes the case of the entire line to capital
- gg=G: Auto indent the whole file.
- gUit:Capitalize all words inside a tag.

## Insert Mode
- ctrl h : Delete one character back
- ctrl w : Delete back one word
- ctrl u : Delete back start of the line.
- yt, : yanks the word till ,
- ctrl r + 0 : pastes the yanked text from register in insert mode.
- ctrl r + = : opens a bottom where we can do calculation after that press enter
- ctrl v + (any ascii code) : gives the letter for example ctrl v 065 => A

## Replace Mode
- R : replace mode the line length doesn't change it overwrites the characters.
- gR : same as above but treats the tab character as thought it consisted as spaces.

## Visual Mode
- v : Enable character-wise visual mode
- V : Enable line-wise visual mode
- ctrl+v:Enable block wise visual mode
- gv : Reselect the last visual selection
- o : Go to the other end of highlighted text
- Vj + > : Indents the selected lines
- vit : visually select inside a tag
- Vr- : replace the whole line with -
- trick : ctrl v jj$ followed by A; and then escape , inserts ; to the end of each line.

## Command Mode
- : command mode
- /: search prompt
- ctrl r= : to access expression register
- :edit : read file to edit
- :write : write file
- :tabnew : opens up a new tab
- :tabclose: closes up the current tab
- :split : split windows
- :ctrl w + movement keys (jklh) for toggling between panes
- :q to quit a pane
- :only to quit all other panes except the current pane
- ctrl w : delete a word backward to the start of previous word
- ctrl u : delete to the start of the line
- :print {number} : does the corresponding action to the number of lines specified.
- :delete {number} : does the corresponding action to the number of lines specified.
- :join {number} : does the corresponding action to the number of lines specified.
- :substitute {number} : does the corresponding action to the number of lines specified.
- :normal {number} : does the corresponding action to the number of lines specified.
- :action {start}, {end} : we can also specify the start and end of the lines.




