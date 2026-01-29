# Git Commands Cheat Sheet with Usage

## 1. Configuration Commands

### git config --global user.name "Your Name"
**What it does:**  
Sets the name attached to all your commits.

**When to use:**  
Once, when setting up Git on a new system.

---

### git config --global user.email "your.email@example.com"
**What it does:**  
Sets the email attached to commits.

**When to use:**  
Once during initial Git setup.

---

## 2. Initializing & Cloning

### git init
**What it does:**  
Creates a new Git repository in the current folder.

**When to use:**  
When starting a new project locally.

---

### git clone `<url>`
**What it does:**  
Downloads a remote GitHub repository to your computer.

**When to use:**  
When you want to work on an existing project.

---

## 3. Staging & Committing

### git status
**What it does:**  
Shows modified, staged, and untracked files.

**When to use:**  
Before and after `git add` or `git commit`.

---

### git add .
**What it does:**  
Adds all modified and new files to the staging area.

**When to use:**  
Before committing multiple related changes.

---

### git commit -m "message"
**What it does:**  
Saves a snapshot of staged changes.

**When to use:**  
After staging files you want to permanently save.

---

## 4. Working with Remotes (GitHub)

### git remote add origin `<url>`
**What it does:**  
Connects your local repo to GitHub.

**When to use:**  
Once, before the first push.

---

### git push origin `<branch>`
**What it does:**  
Uploads commits to GitHub.

**When to use:**  
After committing changes locally.

---

### git pull origin `<branch>`
**What it does:**  
Fetches and merges changes from GitHub.

**When to use:**  
Before starting new work or when sync is needed.

---

## 5. Branching & Merging

### git branch
**What it does:**  
Lists all branches.

**When to use:**  
To check which branch you are on.

---

### git checkout -b `<branch>`
**What it does:**  
Creates and switches to a new branch.

**When to use:**  
Before starting a new feature.

---

### git merge `<branch>`
**What it does:**  
Merges the specified branch into the current branch.

**When to use:**  
After finishing a feature.

---

## 6. History

### git log
**What it does:**  
Shows commit history.

**When to use:**  
To review past changes.

