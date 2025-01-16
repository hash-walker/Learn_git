Git Remote
Often our frenemies (read: coworkers) make code changes that we need to begrudgingly accept into our pristine bug-free repos. /s

This is where the "distributed" in "distributed version control system" comes from. We can have "remotes", which are just external repos with mostly the same Git history as our local repo.

When it comes to Git (the CLI tool), there really isn't a "central" repo. GitHub is just someone else's repo. Only by convention and convenience have we, as developers, started to use GitHub as a "source of truth" for our code.

Assignment
Create a second repo called "webflyx-local" as a sibling directory to our original "webflyx" repo.

Use cd, mkdir, and git init to create the new empty repo.

When you're done, your directory structure should look like this:

webflyx/
  - stuff in the original repo
webflyx-local/
  - stuff we'll put in the new repo
Copy icon
Run and submit the CLI tests from inside the new webflyx-local directory.

Tip
The new repo's default branch should be main because that's what we set in our init.defaultBranch config.
Capitalization matters for testing. Be sure the original directory is webflyx and the new directory is webflyx-local. Use mv to rename them if necessary.
