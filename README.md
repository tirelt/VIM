# VIM
Getting started with VIM

## Context

We use VIM to quickly edit files on the fly on servers. On main machine we use VScode with VIM Motion (vscodevim extensio)

## Shortcuts

operator number  motion 
```Vim
h,j,k,l #left,down,up,right
:q # to quite, ! to dsicard changes
:w <Name> # to write, specify name to save as
u # undo
U # undo all the changes of the line
ctrl+r # redo changes
i # to insert mode before the cursor
a # insert after the cursor
A # to insert mode and move at the end of the line
x # delete the character on the cursor
<Esc> # to go back to normal mode
0,$ # go to start,end of the line
<N>w,e # start of the Nth word after cursor
d # delete
<N>dd # delete N lines
d<N>w # delete N words
d$ # delete until end of line
p # put a deleted line below the cursor
r,R # to replace the character,characters of the cursor
ce # to replace the end of a word
cc # to replace the end of a line
c <N> <motion>
Ctrl+G # to show location in the file
G # to move to a line in the file
gg # to start of file
<N>G # to line N
/,? <Enter> # search fwd bakckward
n,N # forward, backward
Ctrl + o,i # go back, go forward
% # jump to closing parenthesis or bracket
:s/old/new/g # to subsitute new for old
:<N>,<M>s/old/new/g  # between line N and M
:%s/old/new/g # replace all
:%s/old/new/gc # with prompt
:!<Command> # to execute an external command
v # to start virtual selection, then : w <Name>, to save
:r <Name> # to insert the content of a file,instead of <Name> we can use !<Command>
o,O # to insert a line below,above the cursor
y #to copy as an operator, yy line, yw one word, y in virtual selection to copy selction
:set # to set opctopns, e.g. 'ic' (ignore casre), 'is' partial match, 'hls' tpo highlight
Ctrl+e # to show possible command, Tab to complete

```
