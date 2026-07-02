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
## 🎯 Resolving Merge Conflicts

When two branches modify the same lines in a file, Git cannot automatically combine the changes. This creates a **merge conflict**.

### Why Merge Conflicts Happen
- Two developers edit the same part of a file
- One branch was created from an older version of `main`
- Changes were made in parallel without frequent syncing

### How to Resolve Conflicts in Visual Studio Code

1. Try to merge (or pull) the branch into `main`
2. VS Code will mark conflicted files with a **Merge Conflict** label
3. Open the file — you will see conflict markers:
   ```text
   <<<<<<< HEAD
   Your current changes
   =======
   Incoming changes from the other branch
   >>>>>>> feature/your-branch-name
4. Decide what the final code should look like:
 - Use the Accept Current, Accept Incoming, or Accept Both buttons in VS Code, or
 - Manually edit the code between the markers
5. Save the file
6. Stage the resolved file
7. Commit the merge resolution
8. Continue with the merge or push
---
### Best Practices to Avoid Conflicts
- Pull from `main` frequently (at least once a day)
- Keep branches small and focused on one feature
- Communicate with teammates when working on overlapping areas
- Use meaningful commit messages so changes are easier to understand

**Important:** Never commit or push a file that still contains conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`). Always resolve conflicts completely first.

---
## 🎯 Pull Requests & Code Reviews

Instead of pushing changes directly to `main`, the recommended team workflow uses **Pull Requests (PRs)**. This enables code review before any changes reach the stable main branch.

### Why Use Pull Requests?
- Maintains stability and quality of `main`
- Enables peer review and knowledge sharing
- Creates a permanent record of discussions and decisions
- Directly supports clean teamwork and quality control (affective learning goal)

### Standard Pull Request Workflow

1. **Push your branch** to GitHub.
2. **Create the Pull Request** — On GitHub, go to your repository and click “Compare & pull request”.
3. **Write a clear description** — Explain what was changed and why (you can reference issues or previous commits).
4. **Request reviewers** — Add team members who should review the code.
5. **Review the code** — Reviewers leave comments, suggestions, or request changes.
6. **Make updates** — Address feedback on your branch and push again (the PR updates automatically).
7. **Approve & merge** — Once approved, merge the PR (common options: “Squash and merge” or “Merge commit”).
8. **Clean up** — Delete the feature branch after it has been merged.
---
## 👉 Practice Tasks

See: [EXERCISES.md](EXERCISES.md)  
[Interactive practice page](https://learngitbranching.js.org/?locale=en_US)  
[Tutorial – VS Code Source Control](https://code.visualstudio.com/docs/sourcecontrol/repos-remotes)

---
**Platform:** GitHub  
**Tool:** Visual Studio Code