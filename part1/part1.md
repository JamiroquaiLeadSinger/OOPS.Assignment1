### 1. List three major version control software for software engineering.
Git, Concurrent Versions System (CVS) and TortoiseCVS are 3 major software for version control.

### 2. What are the main advantages to using Git in your software development, and how is it useful for game developers?
The main advantages to using Git in software development are that it's fast, open-source, free and flexible. For game developers, it's very useful for comparing code and resolving merge conflicts.

### 3. Define the following terms in relation to Git:
#### Branch
A branch is used to work on something different without messing up what everybody else is working on.
#### Pull
Pulling saves changes that other people have made on a repository.
#### Repository
Repositories store code and files, as well as a history of changes to the files and code.
#### Working Copy
A working copy is a repository that's stored locally.
#### Merge
Merging is pushing changes from a side branch onto a different branch.

### 4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git?
Always pull before working, don't push broken code.

### 5. Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
Sublime Merge is a good tool for merge conflicts, and Diffchecker is a good diff tool.

### 6. In a merged source code file, how does Git let you know there is a conflict?
Git will give a list of conflicting files when using the `status` command, or while merging.

### 7. What are the steps you can take to resolve Git conflicts?
1. Check the conflicting files.
2. Find what has changed between the file currently in the repository and the local file.
3. Use a merge tool or manually change the files so that nothing is lost.

### 8. What does git revert do, and how can you use it?
Git Revert safely undoes changes from commits. You can use it to return a game to a previous version if the new one is buggy.

### 9. What does git reset do, and how can you use it? 
Git Reset undoes every change after a certain commit and deletes every commit after it. Git Reset can be used to go back to a previous version in the event of a catastrophic issue.

### 10. What is the difference between git revert and git reset?
Git Revert keeps all changes after the commit that you reverted to, while Git Reset removes them.

### 11.	True or False: It is okay to commit broken code to the main branch.
FALSE!!!

### 12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True, because if one change causes bugs, you can revert and keep the other change.

### 13. Describe what is DevOps, how is it useful for game developers?
DevOps automates certain actions during development.