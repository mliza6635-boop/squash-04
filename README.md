# Lab 4: Squash — Clean Up Small Commits

Starter file:
- `deploy.py` — base program on `main`.

Follow the tasks in the assignment sheet:
1. Create `feature-deploy` from `main`.
2. Make a small change to `deploy.py` and commit it. Repeat two more times (three small commits total).
3. View commit history with `git log --oneline`.
4. Run `git rebase -i HEAD~3`.
5. In the editor, keep the first commit as `pick` and change the next two to `squash` (or `s`).
6. Write a clean final commit message, e.g. "Add deployment helper".
7. View the history again with `git log --oneline`.
