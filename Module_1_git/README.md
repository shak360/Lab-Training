### Some BASH commands (don't forget to remove the angle brackets and replacing what is inside with the relevant argument):

- `cd <directory name>` - change directories to the directory you've input
- `ls` - list the files in the current directory
- `pwd` - print working directory (prints the path of your current location)
- `mkdir <new directory name>` - make a new directory with the name you've input
- `cp <source file path> <target file path>` - copy a file from one location to another using the paths you've input

### Git commands (don't forget to remove the angle brackets and replacing what is inside with the relevant argument):

- `git status` - gives you the status of your current git tracked repository and files

Use this to check what branch you're on, what files needed to be tracked, commited, and pushed. This _won't_ tell you if you need to `git pull` a branch to update your repository.

- `git branch <name of new branch>` - create a new branch with the name as entered in angle brackets

Your branch name should follow the pattern `<first initial><last initial>-<purpose>` where you should have a one or two word phrase in `camelCase` describing the changes you plan to make. Try to avoid spaces in branch names (and in naming anything in general). Use underscores (`snake_case`) or `camelCase` wherever you can.

- `git checkout <name of branch>`

- `git add -A` 

- `git commit -m "<helpful description>"`

- `git push`
