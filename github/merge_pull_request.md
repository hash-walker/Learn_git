Merge Pull Request
In a typical team workflow, you would ask a team mate to review your pull request. If they approve of the changes, they would approve the pull request, and you'd be clear to merge.

We're the dictators of our own repo however, so no need to wait for approval!

Assignment
Merge the pull request on GitHub to bring the remote add_classics branch into the remote main branch. You should see that it added 4 commits.
Switch back to your main branch locally.
Run git pull origin main to bring the changes from the remote main branch to your local main branch. You should see a fast-forward merge.
Delete the local add_classics branch: git branch -d add_classics
