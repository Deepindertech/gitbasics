## Daily Notes – Git Practice

## Date
Today

## What I practiced
- Understanding `git clone` vs `git pull`
- Daily workflow in a team project
- Creating a feature branch for each task
- Adding files and committing changes
- Pushing feature branches to GitHub
- Creating and merging Pull Requests (PR)
- Cleaning up branches after merge

## Team workflow understanding
- There is only **one shared `main` branch**
- The manager controls merges into `main`
- Each developer works on their **own feature branch**
- All changes go to `main` via Pull Requests

## Important Git rules I learned
- Clone the repository **only once**
- Pull `main` daily before starting work
- One task = one feature branch
- Never push directly to `main`
- PR is required to merge code into `main`

## Commands I practiced
```bash
git checkout main
git pull origin main
git checkout -b feature/add-daily-notes
git add daily-notes.md
git commit -m "Add daily notes for Git practice"
git push origin feature/add-daily-notes
