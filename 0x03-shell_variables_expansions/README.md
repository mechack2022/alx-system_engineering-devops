# __SHELL_VARIABLES EXPANSIONS__
## TABLE
 | script                  | function |
 | --------                | -------- |
| Option | Description |
| ------ | ----------- |
| `set`  | list all local variable, envronmental variable and functions. |
| `printenv` | list all environmental variables |
| `export PATH="$PATH:/action"`   | add /action to the PATH. /action is the last directory to check directory |
|`alias ls ="rm *" `   | Create a script that creates an alias. Name: ls Value: rm * |
| `echo hello $USER`      | Create a script that prints hello user, where user is the current Linux user |
|`BEST="School"` | create new local variable called School |
|`export BEST="School"` | create a new global variable with the value School |

