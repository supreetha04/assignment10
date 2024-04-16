1. git init
2. git remote -v
3. Create a repository in github
4. git remote add origin https://github.com/supreetha04/assignment10.git
5. git checkout -b test ------create test branch
6. git checkout -b master
7. git merge test
8. checkout to master and make some changes
9. git merge --no-ff test




Difference Between Option A and Option B:
The primary difference lies in how the branch history is represented:
Fast-Forward Merge (Option A): Simple and linear. No new commit is created; the branch pointer moves forward.
Non-Fast-Forward Merge (Option B): Creates a new merge commit, explicitly indicating that a merge occurred, even if there were no conflicts.
Use fast-forward merges when you want a clean, linear history. Use non-fast-forward merges when you want to preserve the branch structure or when multiple developers are working on the same branch.