# Git Return ↩️

A script to easily return you to the default branch and start anew!

## Worktrees
To use worktrees, run `git config core.gitreturnworktree true`.

## Usage
You can use `git_return setup` to start setting up the utility.
`git_return` will take you to the default branch and begin updating based
on your package manager. Then offer you to create a new branch.  

`git_return --prev` lets you return to the branch made prior to the current branch.
`git_return --next` lets you go to the branch made after the current branch.

Note: only works with `git_return` created branches.  
Note: the above functions only print the branches from before and after if you are using worktrees.  
