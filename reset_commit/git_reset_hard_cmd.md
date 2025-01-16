Git Reset Hard
In the last lesson, we undid a commit but kept the changes. We don't want to keep the changes to titles.md, here's how to reset those changes.

git reset --hard COMMITHASH
Copy icon
This is useful if you just want to go back to a previous commit and discard all the changes.

Assignment
Run git status to confirm a staged change that modified the titles.md file.
Run git reset --hard <I commit hash> to undo the change.
Check to make sure the titles.md file is reset:
git status
