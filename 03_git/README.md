# Git

Locally, we have...
 - a Working Directory (WD)
 - a Staging Area (SA)
 - a Commit History (CH)

On GitHub, we can create...
 - a Remote Repository (RR)

Local set-up commands:
```
git init    # Initialize the directory with a .git/ folder
git status  # See what git is thinking
git add <file/folder name>  # Adds file from WD to SA
git commit                  # Moves file from SA to CH
git log                     # Show my CH
```

Updating GitHub with local changes
```
git remote add origin <repo SSH address> # Name RR origin
git push -u origin main     # Back up my changes on RR
```

Branching
```
git checkout -b <new branchname>  # Create a new local branch
```
