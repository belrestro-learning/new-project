# new-project

## Developing new features

to work on new features you need to checkout to a new branch without affecting main branch

`git checkout -b development` or `git branch development && git switch development`

once your changes are ready to commit use

`git add .` and `git commit -m "message"` to stage and describe your changes

to deliver your changes to main branch switch to a main branch

`git checkout main` or `git switch main`

and merge your changes to branch

`git merge development`
