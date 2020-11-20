---
authorinformation: null
---

# Linking local branches to remote branches

After creating a local branch, you still have to set up a relationship between that branch and a remote branch.

1. Type one of the following:
   * `git push -u origin <branch name>`: Publish a local branch on the remote for the first time and tell Git to track the newly created remote branch.
   * `git checkout --track origin <branch name>`: Link your working branch to an existing remote branch.
   * `git branch -u origin/<branch name>`: Change a tracking relationship for your current HEAD branch.
2. Press Enter.

