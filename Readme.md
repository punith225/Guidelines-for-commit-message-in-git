# 📌 Git Commit Message Guidelines

## 📝 What is a Commit Message?

A **commit message** is a brief explanation of the changes you made in your project. It helps you and your team members understand what each commit does without having to check the actual code changes.

### **Why are commit messages important?**
✅ Makes it easy to track changes in the project history.  
✅ Helps team members understand why a change was made.  
✅ Useful when debugging or rolling back to previous versions.  
✅ Essential for maintaining a clean and professional Git repository.  

---

## ⚙️ How to Write a Commit Message in Git?

### **Using the command line:**
You can write a commit message directly using the `-m` flag:
```sh
git commit -m "Fix broken image links in homepage"
```
This creates a commit with the message `"Fix broken image links in homepage"`.

### **Using the editor method:**
If you run the `git commit` command without `-m`, Git will open a text editor where you can write a more detailed commit message.

```sh
git commit
```
Then, inside the editor, you can write:
```
Fix login form validation error

- Fixed an issue where users couldn't submit the form with a valid email.
- Updated error messages for better clarity.
- Added test cases to verify validation logic.
```
Save and exit the editor to complete the commit.

---

## ✨ Best Practices for Writing Good Commit Messages

🔹 **Keep the subject line short (max 50 characters).**  
🔹 **Capitalize the first letter of the subject line.**  
🔹 **Don't put a period (.) at the end of the subject line.**  
🔹 **Leave a blank line between the subject and the body.**  
🔹 **Write the subject in the imperative mood.** (e.g., "Fix bug" instead of "Fixed bug" or "Fixing bug")  
🔹 **Explain what the commit does, not how it does it.**  

### **Example of a Well-Written Commit Message:**
```
feat: Add dark mode toggle to the settings page

- Implemented a toggle switch in the settings page to enable dark mode.
- Integrated dark mode styles using CSS variables.
- Stored the user's preference in localStorage to persist mode across sessions.
```
---

## 🔹 What is the Imperative Mood?
**The imperative mood** is a command or instruction (e.g., "Fix bug" instead of "Fixed bug" or "Fixing bug").

🚫 **Bad Examples:**  
❌ Fixed the login error.  
❌ Fixing the login error.  

✅ **Good Example:**  
✔️ Fix the login error.  

---

## 🎯 Types of Commit Messages (with Examples)

| **Type**       | **Description**                                        | **Example** |
|---------------|------------------------------------------------|------------|
| `new`        | for new feature implementing commit               | `new: Implement AI assistant` |
| `feat / feature` | for new feature implementing commit (equal `new`) | `feat: Add payment gateway` |
| `update`     | for update commit                                 | `update: Improve dashboard layout` |
| `bug`        | for bug fix commit                                | `bug: Fix checkout page crash` |
| `security`   | for security issue fix commit                     | `security: Patch XSS vulnerability` |
| `performance`| for performance issue fix commit                  | `performance: Optimize image loading` |
| `improvement`| for backwards-compatible enhancement commit       | `improvement: Enhance search functionality` |
| `breaking`   | for backwards-incompatible enhancement commit     | `breaking: Remove legacy API support` |
| `deprecated` | for deprecated feature commit                     | `deprecated: Mark old payment method as deprecated` |
| `i18n`       | for i18n (internationalization) commit            | `i18n: Add French translations` |
| `a11y`       | for a11y (accessibility) commit                   | `a11y: Improve keyboard navigation` |
| `refactor`   | for refactoring commit                            | `refactor: Modularize authentication service` |
| `docs`       | for documentation commit                          | `docs: Update API documentation` |
| `example`    | for example code commit                           | `example: Add sample config files` |
| `test`       | for testing commit                                | `test: Add unit tests for user model` |
| `deps`       | for dependencies upgrading or downgrading commit  | `deps: Upgrade React to v18` |
| `config`     | for configuration commit                          | `config: Update ESLint rules` |
| `build`      | for packaging or bundling commit                  | `build: Optimize Webpack config` |
| `release`    | for publishing commit                             | `release: Prepare v2.0.0` |
| `wip`        | for work in progress commit                       | `wip: Initial setup for new module` |
| `chore`      | for other operations commit                       | `chore: Clean up unused files` |

---

## 🚀 Why Should You Follow These Guidelines?
✅ Helps new developers understand the project history.  
✅ Keeps the Git log clean and readable.  
✅ Makes debugging easier in the future.  
✅ Ensures consistency in team-based projects.  
✅ Improves collaboration by making changes self-explanatory.  

---

## 📚 Additional Resources
- [FreeCodeCamp: Writing Good Commit Messages](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)
- [TheServerSide: Git Commit Message Guidelines](https://www.theserverside.com/video/Follow-these-git-commit-message-guidelines)

---

## 🌟 Summary
- **Write clear, concise commit messages.**
- **Use the imperative mood (e.g., "Fix bug" instead of "Fixed bug").**
- **Follow the structure: `type: Subject`, followed by a description if needed.**
- **Keep commit messages meaningful and useful for future reference.**

---


