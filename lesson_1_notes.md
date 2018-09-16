# Commands
| Code                                            | explanation                                                  |
| ----------------------------------------------- | ------------------------------------------------------------ |
| `git clone URL`                                 | clone a repository (remote is automatically set to the GitHubURL) |
| `git log`                                       | view history of repository (press *q* for quit)              |
| `git log -n1`                                   | see only the message of last commit                          |
| `git log --graph --oneline master experimental` | see the visual representation of the commit history          |
| `git diff oldID newID`                          | compare to versions in repository (four characters of commit ID are sufficient) |
| `git diff`                                      | compare working directory with staging area                  |
| `git diff --staged`                             | compare staging area with commit 1 (most recent/last commit) |
| `git show`                                      | show changes introduced by a commit compared to its parent   |
| `git checkout ID/branch`                        | with an oldID you can switch to an old version<br />with the newID you can switch back to the most recent version |
| `git init`                                      | create /.git and make a repository from the actual directory and the subdirectories |
| `git status`                                    | show which files have changed since the last commit          |
| `git reset file`                                | remove file from staging area                                |
| `git reset --hard`                              | remove changes from working directory and staging area       |
| `git branch`                                    | get an overview of all branches                              |
| `git branch experimental`                       | create a new branch with the name *experimental*             |
| `git gc`                                        | start Git's garbage collection manually                      |
| `git merge master experimental`                 | merge two branches                                           |
| `git merge --abort`                             | restore files to their state before you started the merge    |
| `git remote`                                    | see all the current remotes (-v for more informations)       |
| `git remote add origin GitHubURL`               | add the repository on GitHub as a remote                     |
| `git push origin master`                        | send repository to the remote                                |
| `git pull origin master`                        | same as `fetch origin` and then `git merge master origin/master` |
| `git fetch origin`                              | update alle the copies of every branch from the origin remote (which is called origin/master) |


# Keyboard Commands
Press `q` to exit `git log` and `git diff`.

# Configurations
| Code                                | explanation             |
| ----------------------------------- | ----------------------- |
| `git config --global color.ui auto` | get colored diff output |

# Notes

| Code                  | explanation                                                  |
| --------------------- | ------------------------------------------------------------ |
| *HEAD*                | git's name for the current commit                            |
| *master*              | git's name for the master branch (official branch with working version) |
| *working directory*   | directory your working in and make your changes              |
| *staging area*        | area where files are added in order to use them for the next commit |
| *repository*          | area where all commits are saved                             |
| *origin*              | default name for remote on GitHub (after making a fork, origin points to the fork) |
| *upstream*            | name for remote on GitHub pointing to the original remote after making a fork |
| *branch*              | ?                                                            |
| *clone*               | a copy of the repository on the local computer or from GitHub to the local computer |
| *fork*                | a copy of a repository from GitHub to GitHub                 |
| *fast-forward merges* | merge of two commits, where one commit is reachable by the other |

# Useful Links

* [Udacity Styleguide](http://udacity.github.io/git-styleguide/)
* [Resolving a merge conflict using the command line](https://help.github.com/articles/resolving-a-merge-conflict-using-the-command-line/)

