# Git Assignment

Git and GitHub Assignment for DevWeekends - Main Branch

## Merge vs Rebase

**Merge** and **Rebase** are both Git operations used to combine changes from one branch into another, but they work differently.

### Merge
- Merge combines two branches by creating a **new merge commit**.
- It preserves the complete history of both branches.
- It is the safest approach for team collaboration.
- Merge is commonly used when merging a Pull Request (PR) on GitHub.

### Rebase
- Rebase moves the commits of one branch on top of another branch.
- It creates a **clean and linear commit history**.
- It does not create a merge commit.
- Rebase rewrites commit history, so it should be used carefully, especially on shared branches.

## Key Differences

| Merge | Rebase |
|--------|---------|
| Creates a merge commit. | Does not create a merge commit. |
| Preserves the original commit history. | Rewrites commit history. |
| Safe for collaborative projects. | Best for keeping local history clean. |
| Branch history remains visible. | Creates a clean and linear history. |

## Conclusion

For this assignment, I used **Merge** by creating Pull Requests (PRs) and merging my feature branches into the `main` branch. **Rebase** is useful for maintaining a clean commit history before merging changes.
