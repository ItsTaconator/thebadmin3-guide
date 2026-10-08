# Linux Commands
This is a short list of the most useful commands on the server, since I'm assuming most people interacting with it won't be Linux users.
| Command          | Description | Windows Equivalent (PowerShell) |
| -------          | ----------- | ------------------------------- |
| `ls`             | Lists files in a directory | `Get-ChildItem` (`ls` works as an alias) |
| `cd <directory>` | Lets you change to a different directory | `Set-Location` (`cd` works as an alias) |
| `sudo <command>` | Lets you run a command with superuser privileges (administrator) | `Start-Process <command> -Verb RunAs` |
| `su <username>`  | Lets you switch to a different user | N/A |
| `cat <filename>` | Read contents of file | `Get-Content` |
| `nano <filename>` | Edit file (simple) | N/A |
| `vim <filename>` | Edit file (advanced) (`:wq` will be very useful) | N/A |