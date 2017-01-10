inputx
=================================================================================

The standard `\input` command looks for files in the current working directory 
(and in `$TEXINPUTS` and `\input@path`) to find the files given to it.
Sometimes it is desirable to change the current working directory, if not, any 
recursive `\input` will look in the wrong place. This package fixes this 
problem.

