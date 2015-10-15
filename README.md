# Learning the vi editor (book notes)

_vi commands_
- i - insert mode
- ZZ - write and quit
- h, j, k, l - move cursor in one direction keys
- 4l - move the cursor four times to the left (can pretty much prepend a number arg to any command)
- 0 - move to the beginning of a line
- $ - move to the end of a line
- w - move to the next word
- b - move to the prev word
- o - insert a new line below
- O - insert a new line above
- a - append (better than i at the end of a line)
- x - delete character
- cw - change word (deletes from cursor to end of word and goes into insert mode)
- r[char] - replace with [char]
- cw - change to end of word
- cb - change to beginning of word
- c2b - change back two words
- c$ - change to end of line
- C - change to end of line (equivalent to c$)
- c0 - change to beginning of line
- cc - change line

vi commands often follow the format: (command)(number)(text object)
which is equivalent: (number)(command)(text object)

_ex commands_
- :e! - revert all changes in the session to original file
- :q! - revert all changes in session and quit vi
- :! - having a bang at the beginning of a command let's you UNIX (i.e. !rm somefile)
- :w [new filename] - write to a new location
- :w! - overwrite file
- :set wm=10 - set the wrap margin to 10 characters
- :set nu - set number lines
