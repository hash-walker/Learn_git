Git Push
The git push command pushes (sends) local changes to any "remote" - in our case, GitHub. For example, to push our local main branch's commits to the remote origin's main branch we would run:

git push origin main
Copy icon
You need to be authenticated with the remote to push changes, which you should have done in the last lesson.

Alternative Options
You can also push a local branch to a remote with a different name:

git push origin <localbranch>:<remotebranch>
Copy icon
It's less common to do this, but nice to know.

You can also delete a remote branch by pushing an empty branch to it:

git push origin :<remotebranch>
Copy icon
Assignment
Let's push our local main branch to the remote origin repo for safekeeping!

In your local webflyx repo, switch back to main. It's most recent commit should be G.
Run git push origin main.
Navigate to your GitHub repo in your browser and make sure that all the files and commits from your local main branch are there.
