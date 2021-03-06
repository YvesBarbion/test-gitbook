---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Conflicts

## About a conflict

A conflict in a file is the result of two or more collaborators who made changes to the same file and try to the synchronize the file.

In the figure below you find a typical workflow. Two collaborators start to work on a local copy of the same source. When collaborator 1 uploads the updated content to the cloud, there will be no conflicts. Only when collaborator 2 uploads the content, you can get potential conflicts.

![](../../../../.gitbook/assets/git-usecase-conflict.png)

## When do you get a conflict

* You deleted a file and a collaborator made changes in his version of the file.
* You and a collaborator made a change to the same line in a file.

## When do you not get a conflict

* You deleted a file and the collaborator didn't make any changes to the file. In that case the files is deleted.
* You and the collaborator made changes on different lines in the same file. In that case the files are merged automatically.

