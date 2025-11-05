# 📘 Git Command Note

## 🧠 Command
git config --global init.defaultbranch main

---

### 🧩 Description
Sets the **default branch name** for all new Git repositories you create.

---

### 🔍 Breakdown

| Part                 | Meaning                                                         |
| -------------------- | --------------------------------------------------------------- |
| git config           | Used to set Git configuration values.                           |
| --global             | Applies the setting to all repositories on your computer.       |
| init.defaultbranch   | Defines the default branch name when a new repo is initialized. |
| main                 | The branch name you want to use as default.                     |

---

### 💻 Example
When you run:

git init myproject

The first branch will be named **main** instead of **master**.

---

### 💡 Why Use It
GitHub and most modern projects use **main** as the default branch name  
—for **clarity**, **consistency**, and **inclusivity**.

---

### ✅ In Short
> This command makes **main** your default starting branch for all new Git repositories.
