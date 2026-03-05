# Git Commands Cheat Sheet

## Initialize Repository
```bash
git init
```

## Check Repository Status
```bash
git status
```

## Add Files to Staging Area

Add a single file:
```bash
git add filename.py
```

Add all files:
```bash
git add .
```

## Commit Changes
```bash
git commit -m "commit message"
```

## View Commit History
```bash
git log
```

Short version:
```bash
git log --oneline
```

## Connect to Remote Repository
```bash
git remote add origin https://github.com/username/repository.git
```

## Push Code to GitHub
```bash
git push -u origin main
```

## Pull Latest Changes
```bash
git pull origin main
```

## Clone Repository
```bash
git clone https://github.com/username/repository.git
```

## Branching

Create branch:
```bash
git branch branch-name
```


Switch branch:
```bash
git checkout branch-name
```

Create and switch branch:
```bash
git checkout -b branch-name
```

## Merge Branch
```bash
git merge branch-name
```

## Delete Branch
```bash
git branch -d branch-name
```
