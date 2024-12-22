# ASSIGNMENT

# WHAT IS VERSION CONTROL

Version control is the practice of tracking and managing changes to software code increasing teeam efficiency. Version control systems are software tools that help software teams manage changes to source code over time. It is also known as source control


# EXPLAIN ThE DIFFERENCE BETWEEN GIT AND GITHUB

Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

# LIST 3 OTHER GITHUB ALTERNATIVES

GitLab
Bitbucket
SourceForge

# EXPLAIN THE DIFFERENCE BETWEEN GIT FETCH AND GIT PULL

GIT FETCH:

Downloads changes from a remote repository but doesn’t apply them to your local branch.
Think of it as “checking for updates” without changing anything locally.

GIT PULL:

Downloads changes and merges them into your current branch.
Combines git fetch and git merge in one command.

#  EXPLAIN GIT REBASE AND THE COMMAND FOR IT.

GIT REBASE 
Think of rebase as “rearranging history. ”It moves changes from one branch and places them on top of another branch. It’s used to keep a cleaner and linear project history.

COMMAND 

```bash
Copy code
git rebase <branch-name>
```

For example, to rebase your feature branch on main:

```bash
Copy code
git checkout feature
git rebase main
```

# EXPLAIN  GIT CHERRY-PICK AND THE COMMAND FOR IT 
GIT CHERRY-PICK 
Cherry-picking is like “picking a single change” from one branch and applying it to another. Useful when you want to copy a specific commit without merging the whole branch.

Command for git cherry-pick:
```bash
Copy code
git cherry-pick <commit-hash>
```

For example, to pick a commit with hash abc123:

```bash
Copy code
git cherry-pick abc123
```

