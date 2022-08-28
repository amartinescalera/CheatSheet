# Git Comands

This is a small repository where I am going to push some basics. The basic commands that we can extract from a sheet cheat. They are:

| Comando | Description |
| --- | --- |
| git push | Pushea the current Branch. |
| git reset [file] | unstage a file while retaining the changes in working directory |
| git diff | diff of what is changed but not staged |
| git diff --staged | diff of what is staged but not yet committed |
| git commit -m “[descriptive message]” | commit your staged content as a new commit snapshot |
| git config --global user.name “[firstname lastname]” | set a name that is identifiable for credit when review version history |
| git config --global user.email “[valid-email]” | set an email address that will be associated with each history marker |
| git branch | list your branches. a * will appear next to the currently active branch |
| git branch [branch-name] | initialize an existing directory as a Git repository |
| git clone [url] | retrieve an entire repository from a hosted location via URL |
| git log | show the commit history for the currently active branch |
| git log branchB..branchA | show the commits on branchA that are not on branchB |
| git remote add [alias] [url] | add a git URL as an alias |
| git fetch [alias] | fetch down all the branches from that Git remote |
| git rebase [branch] | apply any commits of current branch ahead of specified one |
| git reset --hard [commit] | clear staging area, rewrite working tree from specified commit |
| git rm [file] | delete the file from project and stage the removal for commit |
| git mv [existing-path] [new-path] | change an existing file path and stage the move |
| git stash | Save modified and staged changes |
| git stash list | list stack-order of stashed file changes |
| Logs/
.notes pattern/ | Save a file with desired patterns as .gitignore with either direct string matches or wildcard globs. |
| git config --global core.excludesfile [file] | system wide ignore pattern for all local repositories |

