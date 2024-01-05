# git rebase
`git rebase <branch>`

## Basic
`git rebase main`
:	changes root of current branch to the tip of main

`git rebase` cause conflicts if same file is edited.

1. open conflicted_file and solve conflict

2. `git add conflicted_file`

3. `git rebase --continue`

## Amend message

- `git rebase -i`

- Edit message

- Amend commits
