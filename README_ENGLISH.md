# 🎯 Git & Version Control – Ada Training

This repository serves as a live demo project for practical Ada instruction on Git, branches, and version control in Visual Studio Code.

---
## 📌 Learning Objectives

| Learning Objective | Implementation |
|--------------------|----------------|
| **Cognitive** | Understand what a branch is and why it is used |
| **Psychomotor** | Create, checkout, commit & push a branch in VS Code |
| **Affective** | Develop awareness for clean teamwork |

---
## 🎯 What is a Branch?

A branch is an independent copy of the project in which new features can be developed or bugs can be fixed without affecting the main code (`main`). Once the work is complete, the branch can be integrated (merged) into `main`.

### Why Use Branches?

- **Safety:** The main code remains stable and untouched
- **Parallel Work:** Multiple people can work on different features at the same time
- **Clarity:** Changes are logically organized and easy to follow
- **Quality Control:** Code reviews are possible before changes are integrated

---
## 🎯 Standard Workflow (Visual Studio Code)

1. **Create & checkout branch** – Create a new branch and switch to it
2. **Modify file** – Make your changes and save the file
3. **Commit** – Save the changes with a clear, meaningful commit message
4. **Push** – Upload the changes to GitHub

---
## 📋 Branch Naming Conventions

To keep branches organized and easy to understand, we use the following prefixes:

- `feature/...` – New features (e.g. `feature/login-form`)
- `fehlerbehebung/...` – Bug fixes (e.g. `bugfix/password-reset`)
- `dokumentation/...` – Documentation updates (e.g. `documentation/readme-update`)
- `test/...` – Tests (e.g. `test/unit-tests`)

---
## 💬 Good Commit Messages

A good commit message clearly describes **WHAT** was changed and **WHY** it was changed:

| ✅ Good | ❌ Bad |
|---------|--------|
| `feat: add login form` | `updated` |
| `fix: correct password validation` | `fix` |
| `docs: extend setup instructions` | `changed` |

---
## 👉 Practice Tasks

See: [EXERCISES.md](EXERCISES.md)  
[Interactive practice page](https://learngitbranching.js.org/?locale=en_US)  
[Tutorial – VS Code Source Control](https://code.visualstudio.com/docs/sourcecontrol/repos-remotes)

---
**Platform:** GitHub  
**Tool:** Visual Studio Code