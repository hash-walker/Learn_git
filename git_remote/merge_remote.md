Merge
Just as we merged branches within a single local repo, we can also merge branches between local and remote repos.

Syntax
git merge remote/branch
Copy icon
For example, if you wanted to merge the primeagen branch of the remote origin into your local main branch, you would run this inside the local repo while on the main branch:

git merge origin/primeagen
Copy icon
Assignment
Merge the remote origin/main into the local repo's main branch. Because we are on an empty branch, we should get a nice clean fast-forward merge.

Make sure it worked with git log. You should see all the same commits on your local main branch as you do on the remote origin/main branch.
