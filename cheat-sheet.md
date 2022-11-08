# Cheat Sheet for Command Line and Git 

## Command Line tools

- `ls` - lists te folders in the directory (can be used with `-a or -l`)
- `cd` - changes the working directory in the terminal
- `mkdir` - makes a new folder
- `touch` - creates a file
- `rm` - deletes a file (`rm -r` to delete a folder with contents inside and `-rf` if you are rogue and want to ignore **warnings**)
- `mv [file] [directory]` - to move file 
- `mv [file] [file]` - to change file name
---

## Git Commands
- `git init` - to initialise git in the file
- `git add [filename or .]` - stage files for commit (*use* `.` *if you want all files in the directory to be commited*)
- `git commit -m "[text]"` - add the changes to git (add an extra `-m [text] `**twice** if you want to add **extra** description to the commit message)
- `git remote add origin [ssh-link]` - to initialise the local directory in the github repo
- `git push` - to commit changes to github
- `git clone [ssh-link]` - to clone a repo from GitHub locally
- `git pull` - update the repo from github
