# Git & GitHub Practical Assignment

This project demonstrates **Git repository initialization**, *file ignoring with `.gitignore`*, Markdown documentation, and preparation for publishing the project to GitHub.

## Tools Used
- Git
- GitHub
- Command Prompt / Terminal
- Visual Studio Code or any text editor
- Markdown

## Steps I Took to Initialize the Repository
1. Created a folder named `git-assignment-project`.
2. Opened the terminal and moved into the project folder.
3. Initialized a local Git repository using `git init`.
4. Created the required files: `README.md`, `script.js`, `config.env`, and `.gitignore`.
5. Added `config.env` to `.gitignore` so Git would ignore it.
6. Checked repository status to verify that `config.env` was not being tracked.
7. Added the remaining files to the staging area.
8. Committed the files with an initial commit message.
9. Connected the local repository to a public GitHub repository.
10. Pushed the local `main` branch to GitHub.

## Project Files

| File Name   | Function |
|------------|----------|
| README.md  | Contains project documentation in Markdown format |
| script.js  | Stores a simple JavaScript file for the project |
| .gitignore | Prevents `config.env` from being tracked by Git |

## Example Git Commands
```bash
git init
git status
git add README.md script.js .gitignore
git commit -m "Initial commit with project structure and documentation"
git branch -M main
git remote add origin https://github.com/yourusername/git-assignment-project.git
git push -u origin main
```
