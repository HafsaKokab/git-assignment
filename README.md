# git-assignment
Git and GitHub Assignment for DevWeekends

Merge vs Rebase

Merge and Rebase are both Git operations used to combine changes from one branch into another, but they work differently.

Merge combines two branches by creating a new merge commit. It preserves the complete history of both branches and is the safest approach for team collaboration. This is the method commonly used when merging a Pull Request (PR) on GitHub.

Rebase moves the commits of one branch on top of another branch, creating a linear and cleaner commit history. It does not create a merge commit, but it rewrites commit history, so it should be used carefully, especially on shared branches.

Key Differences
Merge	Rebase
Creates a merge commit.	Does not create a merge commit.
Preserves the original commit history.	Rewrites commit history.
Safe for collaborative projects.	Best for keeping local history clean.
Branch history remains visible.	Creates a linear commit history.
