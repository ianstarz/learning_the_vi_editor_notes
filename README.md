# Learning the vi editor (book notes)

vi commands:
i - insert mode
ZZ - write and quit
h, j, k, l - move cursor in one direction keys
4l - move the cursor four times to the left
0 - move to the beginning of a line
$ - move to the end of a line

ex commands:
:e! - revert all changes in the session to original file
:q! - revert all changes in session and quit vi
:! - having a bang at the beginning of a command let's you UNIX (i.e. !rm somefile)
:w [new filename] - write to a new location
:w! - overwrite file
:set wm=10 - set the wrap margin to 10 characters
:set nu - set number lines
