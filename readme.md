# shcreate - Shell script creator
Create a new shell script on the fly
 - Checks your command is not already in use
 - Generates shell file with shebang
 - Sets executable permissions
 - Writes to ~/bin or user specified directory
 - Generates .bash_profile to home directory (optional)
 - Adds directory to .bash_profile for home root access (optional)
 - Launches file in your favourite editor

# Usage example:
```shcreate [command] [shell directory path (optional)]```

# Getting started
1. Copy shcreate and prmpt to your bin directory (e.g. usr/local/bin)
2. cd to your directory and set permissions of files: `chmod u+x shcreate` and `chmod u+x prmpt`
3. Generate your new shell script `shcreate myshellscript`