# Terminal Cheatsheet for Mac

_Original version [here](https://github.com/0nn0/terminal-mac-cheatsheet/blob/master/README.md with additional commands_
_Letters are shown capitalized for readability only._  _Capslock should be off._

## CORE COMMANDS

| Key/Command | Description |
| ----------- | ----------- |
| cd [folder] | Change directory e.g. `cd Documents` |
| cd |  Home directory |
| cd ~ |  Home directory |
| cd /  | Root of drive |
| ls | Short listing |
| ls -l | Long listing |
| ls -a | Listing incl. hidden files |
| open [file] | Opens a file ( as if you double clicked it ) |
| clear |  Clears the screen |

## COMMAND HISTORY

| Key/Command | Description |
| ----------- | ----------- |
| up arrow |  Cycles through the most recent commands |

## FILE MANAGEMENT

| Key/Command | Description |
| ----------- | ----------- |
| touch [file] |   Create a new file |
| pwd | Full path to working directory |
| . |  Current folder, e.g. `ls .` |
| .. | Parent/enclosing directory, e.g. `ls ..` |
| ls -l .. | Long listing of parent directory |
| cd ../../ | Move 2 levels up |
| rm [file] |  Remove a file, e.g. `rm data.tmp` |
| rm -r [dir] | Remove a directory and contents |
| rm -f [file] | Force removal without confirmation |
| cp [file] [newfile] | Copy file to file |
| cp [file] [dir] | Copy file to directory |
| mv [file] [new filename] |  Move/Rename, e.g. `mv file1.ad /tmp` |

## DIRECTORY MANAGEMENT

| Key/Command | Description |
| ----------- | ----------- |
| mkdir [dir] | Create new directory |
| mkdir -p [dir]/[dir] |  Create nested directories |
| rmdir [dir] | Remove directory ( only operates on empty directories ) |
| rm -R [dir] | Remove directory and contents |

## SHORTCUTS

| Key/Command | Description |
| ----------- | ----------- |
| Tab  | Auto-complete files and folder names |
| Ctrl + L   | Clears the Screen |
| Cmd + K    | Clears the Screen |

## HELP

| Key/Command | Description |
| ----------- | ----------- |
| [command] -h |  Offers help |
| [command] --help | Offers help |
| info [command] | Offers help |
| man [command] |  Show the help manual for [command] |
| whatis [command] | Gives a one-line description of [command] |
| apropos [search-pattern] | Searches for command with keywords in description |
