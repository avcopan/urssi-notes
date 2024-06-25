# Git

## Local

Locally, we have...
 - a Working Directory (WD)
 - a Staging Area (SA)
 - a Commit History (CH)

Local set-up commands:
```
git init    # Initialize the directory with a .git/ folder
git status  # See what git is thinking
git add <file/folder name>  # Adds file from WD to SA
git commit                  # Moves file from SA to CH
git log                     # Show my CH
```

## Remote

On GitHub, we can create...
 - a Remote Repository (RR)

Updating GitHub with local changes
```
git remote add origin <repo SSH address> # Name RR origin
git push -u origin main     # Back up my changes on RR
```

## Branching
```
git checkout -b <new branchname>  # Create a local branch
git push -u origin branching    # Back up new branch on RR
# -u sets the RR branch to track this local branch
```

## Forking
Steps:
1. Fork from org repo through the GitHub web interface
2. Clone your fork to your local machine
3. Then add the org repo as an upstream
```
git remote add upstream <org repo HTTP address>
```

Now we have...
 - my fork as a Remote Repository (origin, RR-O)
 - the org repo as a Remote Repository (upstream, RR-U)
 - my local machine (LM)
