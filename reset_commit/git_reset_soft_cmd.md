Git Reset Soft
The git reset command can be used to undo the last commit(s) or any changes in the index (staged but not committed changes) and the worktree (unstaged and not committed changes).

git reset --soft COMMITHASH
Copy icon
The --soft option is useful if you just want to go back to a previous commit, but keep all of your changes. Committed changes will be uncommitted and staged, while uncommitted changes will remain staged or unstaged as before.

Assignment
Your current branch, update_dune, should be at commit J with a changed titles.md.

Get the I commit hash from git log, then run git reset --soft <hash> to go back to the I commit while keeping the changed titles.md (staged but not commited). J should be gone from the commit log.
