# 📘 Git & GitHub Assignment – Module 2

A structured implementation of Git and GitHub workflows as part of **Module 2: Version Control using Git and GitHub**.  
This repository demonstrates initializing a local repository, creating branches, managing commits, working with remote repositories, creating pull requests, and merging changes.

---

## 🚀 Overview

The main objective of this assignment is to apply essential version control skills using Git and GitHub.  
The tasks completed in this project represent a real-world collaborative workflow, involving:

- Repository initialization  
- Branching strategy  
- Commit management  
- Remote repository setup  
- Pull request workflow  
- Merge operations  

---

## 🧩 Tasks Completed

### **1. Local Repository Setup**
- Created a new project directory  
- Initialized Git using `git init`  
- Added a **README.md** file  
- Staged and committed the initial changes  

### **2. Remote Repository Setup**
- Created a new public GitHub repository  
- Connected the local repository using `git remote add origin`  
- Pushed the `main` branch to GitHub  

### **3. Branch Creation & Updates**
- Created a new branch: **feature-update**  
- Switched to the branch  
- Updated README.md / added new files  
- Staged and committed the new changes  

### **4. Push & Pull Request Workflow**
- Pushed the `feature-update` branch to GitHub  
- Opened a Pull Request (PR) to merge into `main`  
- Added a meaningful description to the PR  
- Successfully merged the PR  

### **5. Local Repository Synchronization**
- Switched back to the `main` branch locally  
- Pulled the latest merged changes from GitHub using `git pull`  

---

## 🛠️ Git Commands Used

```bash
git init
git add .
git commit -m "Initial commit"
git branch feature-update
git checkout feature-update
git remote add origin <repository-url>
git push -u origin main
git push -u origin feature-update
git pull
