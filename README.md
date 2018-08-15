# How to Git Good

The completely biased best way to use git on a team

```
git co -b branch_name origin/master
git add -p
git commit -m “Placeholder commit message”
git rebase -i HEAD~$NUM_OF_COMMITS
git commit --amend (add meaningful commit message with full context for PR description)
git fetch
git merge origin/master
git push -f origin branch_name
```
