# 🚀 Master Git !

A modern Git workflow cheat sheet for developers, DevOps engineers, and contributors. This README serves as your quick-reference to the most used Git commands, organized cleanly by use-case.

---

## 📦 Initial Setup

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

## 🧱 Create & Clone Repos

```bash
# Initialize a new repo
git init

# Clone an existing repo
git clone https://github.com/karthik6603/master-git.git
```

---

## 📂 Basic Workflow

```bash
# Check repo status
git status

# Track a new file
git add <filename>

# Add all changes
git add .

# Commit changes
git commit -m "Your commit message"

# Push to remote
git push origin <branch-name>

# Pull latest changes
git pull origin <branch-name>
```

---

## 🌿 Branching Strategy

```bash
# Create a new branch
git checkout -b feature/my-feature

# Switch to a branch
git checkout main

# Merge a branch
git checkout main
git merge feature/my-feature

# Delete a branch
git branch -d feature/my-feature
```

---

## 🧠 Stashing Work

```bash
# Save your work temporarily
git stash

# See list of stashes
git stash list

# Reapply last stash
git stash pop
```

---

## 🧼 Undo & Reset

```bash
# Unstage a file
git reset <filename>

# Undo last commit (keep changes)
git reset --soft HEAD~1

# Undo last commit (discard changes)
git reset --hard HEAD~1
```

---

## 🛠️ Remote Management

```bash
# Add a new remote
git remote add origin https://github.com/user/repo.git

# List remotes
git remote -v

# Remove a remote
git remote remove origin
```

---

## 🎯 Tagging Releases

```bash
# Create a tag
git tag v1.0.0

# Push tags to remote
git push origin --tags
```

---

## 📈 View & Log

```bash
# Log commit history
git log --oneline --graph --decorate --all

# View branches
git branch
```

---

## 🧪 Best Practices

- ✅ Always pull before starting work
- ✅ Use meaningful commit messages
- ✅ Create feature branches for each task
- ✅ Keep main/master clean and deployable
- ✅ Push frequently to avoid local loss

---

## 📄 License

Licensed under MIT. Feel free to use, share, and enhance!

---

## 🤝 Contributing

If you find this useful, give it a ⭐. Contributions welcome!

---

> “Code is like humor. When you have to explain it, it’s bad.” – Cory House
