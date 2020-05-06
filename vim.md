# VIM
`vi` improved.
`vim file.txt`
can also use `vimtutor`
[Source](https://www.youtube.com/watch?v=a6Q8Na575qc)
[Notes](https://missing.csail.mit.edu/2020/editors/)

## Modes
Switch between modes : Esc 
* Normal : on starup
* Insert : i insert at the cursor position
* Insert : a insert at the next cursor position
* Insert : s remove letter and insert at the current position
* Insert : o to insert a line and go to insert mode
* Relace : R
* Visual : v (selection mode), Shift-v (line mode), Ctrl-v (block mode)
* Delete : dw delete word, de delete end of the word from cursor
* Delete : dd delete line
* Delete : x delete character
* Change : cc delete line and insert mode
* Change : ce or cw delete upto end of next word and insert mode  
* Undo : u
* Redo : Ctrl-r
* Copy and Paste: yank is copy, so y | yy is to copy current line | yw copy word | p paste  
* Copy in visual mode (bulk) : v and hjkl, press y, press p to paste 
* Copy in visual mode (line mode) : V and same as before, can do rectangular blocks with lh

## Command line
By pressing `:`
:x
:q
:help :w
:sp split text into multiple windows. can work on same file at once. 
:qa quit all open windows

## More keybindings

w move cursor forward by one word
b opposite dir of w
e end of the word
0 begenning
$ end of line
^ goes to first non empty character
~ to change case of word or block
Ctrl u up scroll
Crtl d down scroll
G moves all the way down
gg moves all the way up
L to lowest visible line
M for visible middle line
H for highest 
fo to find first o same for other letters
Fs find first s before cursor
/ search for something, n to match next, p for previous

## Combining with numbers

3k do k 3 times (same for other arrow keys, useful to move)
+4 to move 4 lines forward
-4 to move 4 lines up
2dw delete words twice
c2w change 2 words

## Relevant to programming

%% to jump back and forth between paranthesis, or braces
di( delete everything in the parenthesis
da( delete all in paranthesis

