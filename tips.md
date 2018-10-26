

##### Keyboard Shortcuts
* `Ctrl+a` - Go to beginning of line
* `Ctrl+e` - Go to end of line
* `Ctrl+b` - Go back one character (hold to scroll)
* `Ctrl+f` - Go forward one character (hold to scroll)
* `Ctrl+d` - Delete the next character
* `Ctrl+u` - Delete from cursor to beginning of line
* `Ctrl+w` - Delete the word before the cursor
* `!!` or `sudo !!` - Repeat the current line or repeat the current line as `sudo` respectively
* `!15` - Repeat line 15 from `history` 
* `$_`  - Alias for the value of the argument from the previous command
    * Ex. `cd $_`
* `history` - Show your history of commands if you can't remember what you've done or need to run a previous command again....*or to see what someone else has done*
* `alias` - Create aliases to save yourself from typing common complex commands repeatedly

##### Return Codes
Return codes indicate the outcome of a program running and finishing successfully or not. This is a standard convention for all Linux/Unix software.

* `0` - Program finished successfully
* `1-255` - Program finished with an error
##### Errors
*  1 - Catchall for general errors
*  2 - Misuse of shell builtins (according to Bash documentation)
*  126 - Command invoked cannot execute
*  127 - “command not found”
*  128 - Invalid argument to exit
*  128+n - Fatal error signal “n”
*  130 - Script terminated by Control-C
*  255\* - Exit status out of range
