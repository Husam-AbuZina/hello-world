# hello-world
Learning how to make a repository on GitHub.

## Learning about git Branches
## Tips & Tricks

- Tips
    
    ## Rename a branch
    
    ```jsx
    git branch -m <new-branch-name>
    ```
    
    ## Show all tracked files
    
    ```
    git ls-files -t
    ```
    
    ## Show all untracked files
    
    ```jsx
    git ls-files --others
    ```
    
    ## Stash changes before rebasing
    
    ```jsx
    git rebase --autostash
    ```
    
    ## Undo assume-unchanged.
    
    ```jsx
    git update-index --no-assume-unchanged <file_name>
    ```
    
    ## Restore deleted file.
    
    ```
    git checkout <deleting_commit> -- <file_path>
    ```
    
    ## Restore file to a specific commit-hash
    
    ```
    git checkout <commit-ish> -- <file_path>
    ```
    
    ## List all the alias and configs.
    
    ```jsx
    git config --list
    ```
    
    ## Skip staging area during commit.
    
    ```jsx
    git commit --only <file_path>
    ```
    
    ## List n last commits
    
    ```jsx
    git log -<n>
    ```
    
    ## Clone a single branch
    
    ```
    git clone -b <branch-name> --single-branch https://github.com/user/repo.git
    ```
    
    ## Turn off git colored terminal output
    
    ```jsx
    git config --global color.ui false
    ```
    
    ## Unstaging Staged file
    
    ```
    git reset HEAD <file-name>
    ```
    
    ## Number of commits in a branch
    
    ```jsx
    git rev-list --count <branch-name>
    ```
    
    ## Find common ancestor of two branches
    
    ```
    git merge-base <branch-name> <other-branch-name>
    ```
    
    ## List unpushed git commits
    
    ```
    git log --branches --not --remotes
    ```
    
    ## Backup untracked files.
    
    ```jsx
    git ls-files --others -i --exclude-standard | xargs zip untracked.zip
    ```
    
    ## Show git status short
    
    ```jsx
    git status --short --branch
    ```
    
