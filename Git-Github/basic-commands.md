# 🚀 Git & GitHub Basic Commands Guide

A beginner-friendly guide to the most commonly used Git & GitHub commands during development.

---

# 📌 What is Git?

Git is a **Version Control System** used to:
- Track code changes
- Manage project versions
- Collaborate with teams
- Push projects to GitHub

---

# 🌐 What is GitHub?

GitHub is a cloud platform where developers:
- Store repositories
- Share code
- Collaborate with teams
- Manage projects online

---

# ⚙️ Git Basic Commands

---

# 🏁 Initialize a Git Repository

```bash
git init
```

### 📖 Description
Creates a new Git repository inside your project folder.

---

# 📥 Clone a Repository

```bash
git clone <repository-url>
```

### ✅ Example

```bash
git clone https://github.com/username/project.git
```

### 📖 Description
Downloads an existing GitHub repository to your local system.

---

# 🔍 Check Repository Status

```bash
git status
```

### 📖 Description
Shows:
- Modified files
- Untracked files
- Staged files
- Current branch status

---

# ➕ Add Files to Staging Area

## Add All Files

```bash
git add .
```

## Add Specific File

```bash
git add filename.js
```

### 📖 Description
Moves files to the staging area before committing.

---

# 💾 Commit Changes

```bash
git commit -m "Your commit message"
```

### ✅ Example

```bash
git commit -m "Added React Stopwatch App"
```

### 📖 Description
Saves a snapshot of your changes locally.

---

# ☁️ Push Code to GitHub

## Push to Main Branch

```bash
git push origin main
```

## Push to Master Branch

```bash
git push origin master
```

### 📖 Description
Uploads your local project changes to GitHub.

---

# 📥 Pull Latest Changes

```bash
git pull origin main
```

### 📖 Description
Fetches and updates the latest code from GitHub.

---

# 🌿 Check Current Branch

```bash
git branch
```

### 📖 Description
Displays the current active branch.

---

# 🌱 Create a New Branch

```bash
git checkout -b branch-name
```

### ✅ Example

```bash
git checkout -b feature-login
```

### 📖 Description
Creates and switches to a new branch.

---

# 🔄 Switch Between Branches

```bash
git checkout branch-name
```

### ✅ Example

```bash
git checkout main
```

### 📖 Description
Moves from one branch to another.

---

# 🔀 Merge Branches

```bash
git merge branch-name
```

### ✅ Example

```bash
git merge feature-login
```

### 📖 Description
Combines changes from another branch into the current branch.

---

# 🔗 Check Connected GitHub Repository

```bash
git remote -v
```

### 📖 Description
Shows the remote GitHub repository linked with your local project.

---

# 🔌 Connect Local Project to GitHub Repository

```bash
git remote add origin <repository-url>
```

### ✅ Example

```bash
git remote add origin https://github.com/username/project.git
```

### 📖 Description
Connects your local project with a GitHub repository.

---

# 🕒 View Commit History

## Detailed History

```bash
git log
```

## Short History

```bash
git log --oneline
```

### 📖 Description
Displays all previous commits made in the repository.

---

# ❌ Remove File from Staging Area

```bash
git restore --staged filename
```

### 📖 Description
Removes a file from the staging area without deleting changes.

---

# ♻️ Restore File Changes

```bash
git restore filename
```

### 📖 Description
Restores the file back to the last committed version.

---

# 🗑️ Delete a Branch

```bash
git branch -d branch-name
```

### 📖 Description
Deletes a local branch.

---

# 🚀 Complete Daily Git Workflow

```bash
git status
git add .
git commit -m "Updated project"
git push origin main
```

### 📖 Workflow Steps
1. Check project status
2. Add changes
3. Commit changes
4. Push to GitHub

---

# 📚 Git & GitHub Concepts Learned

- Git Initialization
- Repository Cloning
- Staging Area
- Commit Workflow
- Push & Pull Operations
- Branching
- Merge Workflow
- Remote Repository Connection
- Commit History Tracking
- Markdown Documentation
- GitHub Project Management

---

# 💡 Pro Tip

Always run:

```bash
git status
```

before pushing code to understand the current repository state.

---

# 🎯 Final Note

Git is one of the most important tools for every developer.  
Mastering these commands will help you:
- Build projects professionally
- Collaborate with teams
- Maintain clean project history
- Work efficiently in real-world development