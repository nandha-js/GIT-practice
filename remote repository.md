# 📘 Command: git remote add origin https://github.com/codeiodemo/git.git

### 📝 Description
Connects your **local Git repository** to a **remote repository** (usually on GitHub).

### 💻 Usage
git remote add origin <repository-url>

### 🔍 Breakdown
| Part | Meaning |
|------|----------|
| git remote | Manages connections to remote repositories. |
| add | Adds a new remote connection. |
| origin | The default name for the main remote repository. |
| https://github.com/codeiodemo/git.git | The remote repository URL. |

### 💡 Tip
After adding, push your code using:  
git push -u origin main

### ✅ In Short
> Links your local repo to a remote GitHub repository named **origin**.


# 📘 Command: git branch -M main

### 📝 Description
Renames the **current branch** to **main** (using the `-M` flag to force rename if needed).

### 💻 Usage
git branch -M main

### 🔍 Breakdown
| Part | Meaning |
|------|----------|
| git branch | Used to manage branches in Git. |
| -M | Forcefully renames the branch (even if the name already exists). |
| main | The new branch name. |

### 💡 Tip
Use this after `git init` to rename the default branch from `master` to `main`.

### ✅ In Short
> Renames your current branch to **main**.

# 📘 Command: git push -u origin main

### 📝 Description
Uploads your **local commits** to the **remote repository** on the `main` branch and sets tracking between them.

### 💻 Usage
git push -u origin main

### 🔍 Breakdown
| Part | Meaning |
|------|----------|
| git push | Sends local commits to a remote repository. |
| -u | Sets an upstream link (connects local branch to remote branch). |
| origin | The default name of the remote repository. |
| main | The branch you’re pushing to on the remote. |

### 💡 Tip
After using `-u` once, you can simply run `git push` next time without extra arguments.

### ✅ In Short
> Pushes your code to the **main** branch on GitHub and links it for future pushes.



