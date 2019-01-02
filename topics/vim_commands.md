## Vim commands
vim installation
config in .vimrc
Vim basic commands
 - show line number  :set number
 - insert :i
 - save :w
 - quit :q
 - force quit :q!
 - save and quit :wq

 - delete entire line dd
 - delete N lines Ndd
 - delete word dw
 - delete from middle of line till end Shift+d


 - copy yy
 - copy N lines Nyy
 - paste p
 
 - mark a line mk
 - y'k  copy
 - d'k cut

 - undu u
 - redu Ctrl+r
 
 
 - jump to line number (say :10)
 - Jump to first line (beginning) of file gg
 - Jump to last line (end) of file Shift+g / G
 - Jump to end of line Shift+$
 - Jump to beginning of line 0 (zero)

 - write to next line o
 - write to previous line Shift+o
 - replace single character r
 
 Search
 - /
 - next occurance n
 - previous occurance Shift+n

 Replace
 - :%s/old_word/new_word
 - :%s/old_word/new_word/g (globally)

Previous commands   ESC : UpArrow  

 Switch File
 - :e  same file
 - :e <file name> Switch to file <file name>
 - :e# back to previous file
