Adding a Remote
In git, another repo is called a "remote." The standard convention is that when you're treating the remote as the "authoritative source of truth" (such as GitHub) you would name it the "origin".

By "authoritative source of truth" we mean that it's the one you and your team treat as the "true" repo. It's the one that contains the most up-to-date version of the accepted code.

Command Syntax
git remote add <name> <uri>
Copy icon
Assignment
Inside our new repo, add webflyx as a remote. Give it the name origin. The uri should just be a relative path to the webflyx directory, in our case, ../webflyx.

Run and submit the CLI tests from inside the new webflyx-local directory.
