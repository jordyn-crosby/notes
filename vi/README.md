# vi -- main commands to start using vi


To get out of insertion mode: <esc>


Note:
A number before a command makes vi execute
the command for that number of times.


Moving the text:
^f - next page
^b - previous page
^d - down
^u - up


Moving the cursor:
<number>G - go to the line indicated by <number>
G - go to the last line
- -- previous line
return -- next line
h or backspace -- to the left
l or space -- to the right
k - up one line, same column
j - down one line, same column
w - next word
e - end of the next word
b - previous word 
$ - end of line
^ - beginning of line


Insert:
o - open a line below and insert
O - open a line above and insert
i - insert in the spot
a - insert in the next spot


Moving lines:
>> - move line one tab to the right
<< - move line one tab to the lefta


Delete:
x - delete current character
dw - delete a word starting at the current position
dd - delete the current line


Copy:
yy - copy the current line into a buffer


Paste:
p - paste a buffered line (copied by yy or deleted by dd) or a word (deleted by dw).


Substitute:
r <character> - replace current character by the one given
s <string> - replace current character by the string given
cw <string> - replace the word starting at the current position by the string given


Search:
/<string> - find string in the text (string is a regular expression)
n - next
% - when placed on a (, ), {, }, [, ], finds its match.


Undo
u - undo or redo the last undone command


Repeat:
. - one more time the last command


Save and quit
:w - save
:w <name> - save into file 'name'
:wq - save and quit
:q - quit



