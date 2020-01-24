# Branch Management

| Action | Command | Notes |
| ------ | ------- | ----- |
| Print all local branches |  `git branch` | 
| Print all branches (remote + local) | `git branch -a`
| Go to an existing branch | `git checkout <branch-name>`
| Create a new branch and switch to it | `git checkout -b <branch-name>`
| Delete a local branch | `git branch -d <branch-name>` | `-d` *The branch must be fully merged in its upstream branch, or in HEAD if no upstream was set*
| Delete a local branch | `git branch -D <branch-name>` | `-D` Stands for `--delete --force`, will delete the branch regardless of its merge status
| Delete a remote branch | `git push <remote-name> --delete <branch-name>`

| Action | Command | Notes |
| ------ | ------- | ----- |
| Get the latest updates but don't integrate them | `git fetch --all`