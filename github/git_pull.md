Pull
Fetching is nice, but most of the time we want the actual file changes from a remote repo, not just the metadata.

Command Syntax
git pull [<remote>/<branch>]

The [...] syntax means that the bracketed remote and branch are optional. If you execute git pull without anything specified it will pull your current branch from the remote repo.

Assignment
Let's use the GitHub UI to commit a change to our remote repo. Then we'll pull that change down to our local repo.

Navigate to your GitHub repo in your browser
Ensure the GH repo's main branch's latest commit is G
Navigate to the classics.csv file on the main branch
In the top right corner, click "Edit this file"
Add a new line to the end of the file:
Willow, Ron Howard, 1988
Copy icon
Commit the change using the UI, but change the commit message to: "J: Update classics.csv". No need for an extended description.
On your command line, make sure you're on your main branch.
Run git config pull.rebase false to make sure git will merge on a pull
Merge the changes from the update_dune branch back into main so that main has everything we've done so far (A through I)
Run git pull origin main to pull in the most recent J commit that you made remotely
You should see that it starts a merge commit. Rename the merge commit message to start with K:
Make sure everything worked with git log --oneline. You should have commits "A" through "K" locally.
Delete the update_dune branch locally
Run and submit the CLI tests from inside your webflyx directory.

git pull origin main





