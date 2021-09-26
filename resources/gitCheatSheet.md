# GIT Cheat Sheet

## Basic commands

| Command                     | Description                                                                                                                    |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| git init <directory>        | Create empty Git repo in specified directory.                                                                                  |
| git config user.name <name> | Define author name to be used for all commits in current repo.                                                                 |
| git commit -m "<message>"   | Commit the staged snapshot, but instead of launching a text editor, use <message> as the commit message.                       |
| git status                  | List which files are staged, unstaged, and untracked.                                                                          |
| git log                     | Display the entire commit history using the default format. For customization see additional options.                          |
| git diff                    | Show unstaged changes between your index and working directory.                                                                |
| git remote add <name> <url> | Create a new connection to a remote repo. After adding a remote, you can use <name> as a shortcut for <url> in other commands. |
| git pull <remote>           | Fetch the specified remote’s copy of current branch and immediately merge it into the local copy.                              |
| git push <remote> <branch>  | Push the branch to , along with necessary commits and objects. Creates named branch in the remote repo if it doesn’t exist.    |


## Right heading