# Troubleshooting Git and GitHub

Below is a table of common issues and their solutions for Git and GitHub.

| Issue                           | Description                                                                 | Solution                                                                                                                                                              |
| ------------------------------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Merge Conflicts**             | Git reports a merge conflict when pulling or merging branches.              | Resolve conflicts manually by editing the conflicting files, then run `git add <file>` and `git commit` to complete the merge.                                        |
| **Detached HEAD State**         | Git shows a "detached HEAD" state after checking out a commit.              | Switch back to a branch using `git checkout <branch-name>` or create a new branch with `git checkout -b <new-branch-name>`.                                           |
| **Push Rejected**               | Git rejects a push with the error "non-fast-forward updates were rejected." | Pull the latest changes with `git pull origin <branch>`, resolve any conflicts, and try pushing again.                                                                |
| **GitHub Repository Not Found** | Git cannot find the remote repository on GitHub.                            | Verify the remote URL with `git remote -v` and update it if necessary using `git remote set-url origin <new-url>`.                                                    |
| **Branch Not Found**            | Git cannot find a branch locally or remotely.                               | Fetch all branches with `git fetch --all`, then check out the branch with `git checkout <branch-name>`.                                                               |
| **Accidental Commit on Main**   | Changes were committed to the `main` branch instead of a feature branch.    | Create a new branch from the commit with `git branch <new-branch>`, reset `main` to the previous commit with `git reset --hard HEAD~1`, and switch to the new branch. |
