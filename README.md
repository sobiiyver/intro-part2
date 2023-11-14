# intro-part2

## file paths
### 1. Windows
### Structure: 
### Windows file paths typically start with a drive letter followed by a colon and a backslash, like C:\. Then it follows the folder hierarchy separated by backslashes \. For example, C:\Users\JohnDoe\Documents\file.txt
### 2. macOS
### Structure: 
### macOS file paths do not start with a drive letter. They start from the root directory /, followed by folders separated by forward slashes /. For instance, /Users/JohnDoe/Documents/file.txt
### 3. Relative vs Absolute Paths: 
### Absolute paths start from the root directory (like C:\ on Windows or / on macOS). Relative paths start from the current directory. For example, if your current directory is /Users/JohnDoe, a relative path to a file in Documents would be Documents/file.txt

## Command Line
### Syntax
### command subcommand [options] [arguments]
### Command: This is the primary program you're calling. Examples include git for version control, conda for Anaconda package management, or pip for Python package installation.
### Subcommand: Many command line tools are complex enough to have their own set of subcommands. For instance, in git, subcommands are actions like clone, commit, push, etc. In conda, you might use subcommands like create (for creating environments), install (for installing packages), etc
### "[]" means optional elements. the actual command entered in the command line should not include these brackets.
### [Options]: These are optional modifiers that change how the command or subcommand operates. They are often preceded by a dash (like -m in git commit -m "message")
### [Arguments]: These are the targets or inputs for your command/subcommand. In git clone [url], the URL is the argument for the clone subcommand. In pip install [package], the package name is the argument for the install subcommand.

[command line cheat sheet](https://www.git-tower.com/blog/command-line-cheat-sheet/)

