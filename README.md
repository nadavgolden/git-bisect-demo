## `git bisect` demo

__Objective: find the commit which messed-up the test.__

To find the answer run:
```sh
# git bisect start <bad-commit> <good-commit>
git bisect start HEAD HEAD~10
git bisect run make test
# to stop/reset run
git bisect reset
```

More info [here](https://git-scm.com/docs/git-bisect).