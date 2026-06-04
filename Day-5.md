---
---

--- Before Day-5 ---
I already knew the basics of GitHub repository creation and committing files through the GitHub UI.
--- 

## Day-5 Checklist

- [x] I have set up the basic Git configuration using `git config --global user.name "Your Name"`, `git config --global user.email "your.email@example.com"`, and set the default branch as main using `git config --global init.defaultBranch main`
- [ ] I know GitHub allows only one user account per person, so I have merged my accounts (IITM and personal) into a single unified account
- [x] I understand the three states of a file in Git: working tree → staging → committed
- [x] I can run the daily workflow commands `git status`, `git diff`, and `git log` and know what each shows
- [x] I know how `.gitignore` works and how to use it to ignore files and folders that should not be pushed to the remote repository (e.g., `venv`, `__pycache__`, `.env`)
- [x] I can make a commit: `git add` → `git commit -m "message"` → `git push`
- [x] I know what `origin` and `main` are and can explain them in one sentence each
- [ ] I can set up SSH key authentication and push to GitHub without entering a password
- [ ] I can create an annotated tag (`git tag -a v0.1.0`) and push it to GitHub
- [x] I can write a meaningful commit message (not "fixed stuff" or "final.py")

--- After Day-5 ---
I learned the basic Git workflow, including configuration, staging, commits, pushing, `.gitignore`.
---

--- Feedback (Suggestions for the TDS Team) ---
The Day-5 checklist was useful. A simple Git workflow diagram would make staging, commits, branches, and remotes easier to understand.
---

---
---

Personal Notes:
git status: Shows the current state of files, including modified, staged, and untracked files.
git diff: Shows the exact line-by-line changes made before committing.
git log: Shows the history of commits in the repository.
.gitignore: Tells Git which files or folders should not be tracked or pushed.
origin: The default name for the remote GitHub repository connected to the local project.
main: The primary branch where the main version of the project is maintained.
