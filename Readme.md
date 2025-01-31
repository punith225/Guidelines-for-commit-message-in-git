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

| **Type**      | **Description** | **Example** |
|--------------|---------------|------------|
| **feat**     | A new feature added to the application | `feat: Add dark mode support` |
| **fix**      | A bug fix | `fix: Resolve form validation error for email input` |
| **style**    | CSS changes, formatting, or UI improvements | `style: Update button styles for better accessibility` |
| **refactor** | Code refactoring without adding new features or fixing bugs | `refactor: Optimize data fetching logic` |
| **test**     | Changes related to testing | `test: Add unit tests for login functionality` |
| **docs**     | Documentation updates | `docs: Update README with setup instructions` |
| **chore**    | Maintenance tasks (dependencies, build updates, etc.) | `chore: Update npm dependencies to latest versions` |

---

## 📉 Detailed Examples

### **1. `feat`: Adding a New Feature**
```plaintext
feat: Add multi-language support

- Integrated i18next library for handling translations.
- Added support for English and Spanish languages.
- Created a language switcher dropdown in the navbar.
- Ensured dynamic content updates based on the selected language.
```

### **2. `fix`: Fixing a Bug**
```plaintext
fix: Fix broken navigation menu on mobile devices

- Fixed an issue where the navigation menu wouldn’t open on small screens.
- Adjusted CSS styles to properly align menu items.
- Tested across multiple screen sizes for consistency.
```

### **3. `style`: Styling Updates**
```plaintext
style: Improve hover effects for buttons

- Added smooth transitions for hover effects.
- Adjusted button colors for better contrast and readability.
- Ensured consistency across all pages.
```

### **4. `refactor`: Code Refactoring**
```plaintext
refactor: Simplify API response handling

- Moved duplicate API response processing logic to a helper function.
- Reduced redundant code in multiple components.
- Ensured the refactored function is well-tested and maintains the same functionality.
```

### **5. `test`: Adding or Updating Tests**
```plaintext
test: Add integration tests for user authentication flow

- Created Cypress tests to cover login and logout processes.
- Validated form input fields, error messages, and successful login redirection.
- Ensured proper handling of invalid credentials.
```

### **6. `docs`: Updating Documentation**
```plaintext
docs: Add a setup guide for new contributors

- Created a CONTRIBUTING.md file to explain how to set up the project.
- Added steps for installing dependencies and running the development server.
- Included guidelines for writing commit messages and submitting pull requests.
```

### **7. `chore`: Maintenance Tasks**
```plaintext
chore: Clean up unused files and optimize assets

- Removed old CSS files that are no longer in use.
- Updated `.gitignore` to exclude unnecessary logs and temp files.
- Optimized remaining images for faster load times.
```

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
- [Commitizen CLI](https://github.com/commitizen/cz-cli?tab=readme-ov-file)

---

## 🌟 Summary
- **Write clear, concise commit messages.**
- **Use the imperative mood (e.g., "Fix bug" instead of "Fixed bug").**
- **Follow the structure: `type: Subject`, followed by a description if needed.**
- **Keep commit messages meaningful and useful for future reference.**

---

## 💡 Questions or Feedback?
If you have any questions or suggestions, feel free to share! Happy coding! 🚀

