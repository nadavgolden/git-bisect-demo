## `git worktree` demo

__Objective: work on two branches at the same time__

Solution:
```sh
# git worktree add <path> <branch>
git worktree add ../git-demos-main main
cd ../git-demos-main
# commit some changes

# see changes in the main working tree
cd -
git log

# list your worktrees
git worktree list

# remove a worktree
git worktree remove ../git-demos-main
```

More info [here](https://git-scm.com/docs/git-worktree).
