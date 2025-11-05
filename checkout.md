# 📘 Command: git checkout

### 📝 Description
Used to **switch branches** or **restore files** in your working directory.

### 💻 Usage
git checkout branch-name  
git checkout filename

### 💡 Tips
- Switch to an existing branch  
- Restore a file to its last committed state  
- Use `git switch` (newer alternative) for switching branches

### ✅ In Short
> Moves you to another branch or restores files to a previous state.

# 📘 Command: git checkout <commit-id>

### 📝 Description
Switches your working directory to a **specific commit** in the project’s history.

### 💻 Usage
git checkout <commit-id>

### 💡 Tips
- Use `git log` to find the commit ID (SHA)  
- You’ll be in a **detached HEAD** state (not on any branch)  
- To go back: `git checkout branch-name`

### ✅ In Short
> Lets you view or work with your project at a specific past commit.

# 📘 Command: git checkout -f

### 📝 Description
Forces Git to **switch branches** and **discard local changes** in tracked files.

### 💻 Usage
git checkout -f branch-name

### ⚠️ Warning
All uncommitted changes in tracked files will be **lost**.

### 💡 Tip
Use only when you want a clean working directory without keeping current edits.

### ✅ In Short
> Forces a branch switch and removes all uncommitted changes.


# 📘 Command: git checkout -b

### 📝 Description
Creates a **new branch** and **switches** to it immediately.

### 💻 Usage
git checkout -b branch-name

### 🔍 Breakdown
| Part | Meaning |
|------|----------|
| git checkout | Used to switch branches. |
| -b | Creates a new branch before switching. |
| branch-name | The name of the new branch. |

### 💡 Tip
Use this to start new features or fixes without affecting the main branch.

### ✅ In Short
> Creates and switches to a new branch in one step.
