# Git Branches and Pull Requests

## Important Terminology

- **Pull request:** a request to add all the changes from a branch into the main branch.
- **Reviews:** Get new code checked by team members before merging to main branch

## Commands

| Command                                     | What it does                                                                                                                                           |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `git switch -c BRANCHNAME `                 | creates a new branch                                                                                                                                   |
| `git switch BRANCHNAME `                    | switches to an existing branch                                                                                                                         |
| `git push --set-upstream origin BRANCHNAME` | sets up a connection between new branch and GitHub. (By only writing `git push `you will get an error message with the correct command for connecting) |
