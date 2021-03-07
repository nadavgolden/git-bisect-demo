## `git worktree` demo

__Objective: combine all of the unnecessary commits into one__

Solution:
Use `git rebase` interactive mode:
```
git rebase -i HEAD~10
```

Then squash all of the commits:
```
pick 4ff6943 There
s 449e4a7 are
s 344f897 too
s f181b6c many
s 2361102 commits
s 45cbd6a in
s 720a700 this
s fc48c9e branch.
s 1c0e2d4 Squash
s 20f3552 them!
```
Edit the commit message and you're done!

Feel free to explore more command of `git rebase -i`
