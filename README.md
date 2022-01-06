# Text-Editor
Final project from my computer system class. Make a test editor called WEE.

Gapbuffer - contain text in each line; using the concept of gapbuffer:
  to insert letter at where the cursor is everytime the user types
  move the cursor around whenever the user hit the up, down, left, right arrow keys
  create a new gapbuffer whenever the users hit the enter key
  
Document - a doubly-linked list of Line node, which contains gapbuffer
  create a new line
  insert a line at where the cursor is
  
Window - use ncurses library to print the content of text editor out to the terminal
