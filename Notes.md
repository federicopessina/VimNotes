# Normal Mode

h - go to left \
j - go to lower line \
k - go to upper line \
l - go to right \

H - go to HIGH part of current page \
M - go to MIDDLE part of current page \
L - go to LOW part of current page \

i - enter INSERT mode before the cursor \
a - APPEND after the cursor entering insert mode \
o - OPEN new line under current line and enter insert mode \

I - enter INSERT mode before the line \
A - APPEND after line \
O - OPEN new line above current line and enter insert mode \

w - go to start of the next WORD \
b - go to start of the word BEFORE \
e - go to END of the current word or to END of the next word \

Y - YANK (copy) the full line

u - UNDO \
<CTRL - r> - REDO \

5<down> - move 5 lines to down \
7<up> - move 7 lines to up \
15<right> - move 15 characters to right \
5u - 5 undos

r - REPLACE character (delete char + enter insert mode) \


# Insert Mode

# Visual Mode

v - enter VISUAL mode
v<right> - select from where you are till the end of the word \
d - DELETE what is selected \
y - YANK (copy) what is selected \
p - PASTE what is selected \
c - CHANGE what is selected (delete + enter insert mode) \

dd - DELETE the line \
yy - YANK (copy) the line \
  p - PASTE the line below current line \ 
  P - PASTE the line above current line \
cc - CHANGE the line (delete + enter insert mode) \

D - DELETE the rest of the line (from cursor to right till end of line) \
C - CHANGE the rest of the line (from cursor to right till end of line) \


# Command Mode
:w - WRITE on file \
:q - QUIT \
:q! - QUIT without saving \
