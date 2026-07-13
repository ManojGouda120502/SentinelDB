# Git Workflow

## Repository

Repository Name: AegisDB

GitHub:
https://github.com/ManojGouda120502/AegisDB

---

## Initial Setup

```bash
git init
git branch -M main
git remote add origin https://github.com/ManojGouda120502/AegisDB.git
```

---

## Daily Workflow

### Check Status

```bash
git status
```

### Stage Changes

```bash
git add .
```

### Commit Changes

```bash
git commit -m "docs: add project vision"
```

### Push Changes

```bash
git push origin main
```

### Pull Latest Changes

```bash
git pull origin main
```

---

## Branch Workflow

Create a branch

```bash
git checkout -b feature/login
```

Switch branch

```bash
git checkout main
```

Merge

```bash
git merge feature/login
```

Delete branch

```bash
git branch -d feature/login
```

---

## Commit Message Convention

feat: new feature

fix: bug fix

docs: documentation

refactor: code improvement

test: tests

style: formatting

chore: maintenance

perf: performance improvement

Example

```bash
git commit -m "feat: implement B+ Tree insertion"
```