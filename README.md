# Git Lab 4 – How to Use Git Effectively

## Name

**Abhinav Kumar**

## Roll Number

**1024031186**

## Course

AI for Engineers

---

## Objective

The objective of this lab is to understand and practice the basic commands of **Git and GitHub** for version control. It helps in learning how to create repositories, track changes, manage branches, and push code to GitHub.

---

## Tools Used

* Git
* GitHub
* Command Prompt (Windows)

---

## Steps Performed

### 1. Check Git Installation

Command used:

```
git --version
```

This command verifies that Git is installed on the system.

---

### 2. Configure Git

Commands used:

```
git config --global user.name "Abhinav Kumar"
git config --global user.email "abhinavsaha24@gmail.com"
git config --list
```

These commands set the Git username and email for commits.

---

### 3. Initialize Repository

Commands used:

```
mkdir git_lab4
cd git_lab4
git init
```

This creates a new folder and initializes a Git repository.

---

### 4. Create a File

Commands used:

```
echo "Hello Git" > file.txt
git status
```

A new file is created and Git checks the repository status.

---

### 5. Add File to Staging Area

Command used:

```
git add file.txt
```

This adds the file to the staging area before committing.

---

### 6. Commit Changes

Command used:

```
git commit -m "Initial commit with file.txt"
```

This saves the snapshot of the project in Git history.

---

### 7. Create a Branch

Command used:

```
git branch new_feature
git branch
```

This creates a new branch and lists all branches.

---

### 8. Switch Branch

Command used:

```
git checkout new_feature
```

Switches to the new branch.

---

### 9. Merge Branch

Commands used:

```
git checkout master
git merge new_feature
```

This merges the new branch with the main branch.

---

### 10. Connect to GitHub

Commands used:

```
git remote add origin https://github.com/abhinavsaha24/git_lab4.git
git remote -v
```

This connects the local repository to GitHub.

---

### 11. Push to GitHub

Command used:

```
git push -u origin main
```

This uploads the local repository to GitHub.

---

## Repository Link

https://github.com/abhinavsaha24/git_lab4

---

## Conclusion

This lab experiment demonstrated how to use Git for version control and GitHub for remote repository management. We learned how to track changes, create branches, merge branches, and push code to a remote repository.
