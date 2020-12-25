# VIM baiscs

#### Modes
Esc         Normal mode
i           Insert mode
/           command mode

#### File handling
:w          save the file
:wq         save and quit
:q          dont save and quit

j           move down a line
k           move up a line
h           move to left 
l           move to right

0           go to the beginning of the line
Sh+$        move to end of the line
Sh+^        move to beginning word of th eline

W           move right one word (Ignore punctuations)
w           move forward one word
B           move Backward one word (Ignore punctuations)
b           move backward one word

ctrl+f      page forward
ctrl+b      page backward

m           middle of the program

<number>gg  Go to the line number
gg          Go to the beginning of the file
:0          "-do-"
GG          Go to the end of the file.
:$          "-do-"

Temp:
z + enter   view current line in the top
Sh + ~      Capitalize the current letter

Shift Up    move up by a page 
Shift down  move down by a page 

#### Delete 
x           deletes the current letter (cursor)
X           d
dw          delete a word (forward)
db          delete the word (back)
dd          delete the current line


## Operatiow
Example:
operation{MOTION}
dw - d{w}  - delete {word}
Samples:
d0          Delete from current cursor to the beginning of the line
d$          Delete from current cursor to the end of the line
D           Shortcut for d$

[COUNT]operation{MOTION}
5dw         deletes 5 words to the right
5db         deletes 5 words to the left

[count]operation[count]{motion}
2d3w        2 times - deletes the 3w

[.]
repeats the command

#### Copy paste 
dw          cut
x           cut (same as above)
p           paste after the cursor 
P           paste before the cursor
2p          paste 2 times
y

