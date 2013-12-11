#git-changebranch

A quick, lazy, method of changing branches in git

##Usage

    $ git changebranch
    [0] develop
    [1] master
    [2] release/1.0.4
    [3] remotes/origin/HEAD
    [4] remotes/origin/develop
    [5] remotes/origin/feature/navigation
    [6] remotes/origin/feature/pagespeed-optimization
    [7] remotes/origin/gh-pages
    [8] remotes/origin/hotfix/typo
    [9] remotes/origin/master
    [10] remotes/origin/release/1.0.0
    Select a branch: 2
    Switched to branch 'release/1.0.4'

##Issues

- Does not handle the current branch being detached correctly
- Doesn't create a remote branch locally if it does not exist (is this desired?)
- Handling of user input is .. iffy