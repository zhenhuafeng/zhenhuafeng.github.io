Sourcing is essentially the same as typing each line of the script in at the command prompt one at a time...

Execution starts a new process and then runs each line of the script, only modifying the current environment by what it returns.

interpret is like sourcing but run the script using the given shell interpreter

Dotting is the same as sourcing most of the time (some minor diffs TBD: add a link for the diff)

https://superuser.com/questions/176783/what-is-the-difference-between-executing-a-bash-script-vs-sourcing-it