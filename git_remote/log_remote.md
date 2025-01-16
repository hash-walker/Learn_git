Log Remote
The git log command isn't only useful for your local repo. You can log the commits of a remote repo as well!

git log remote/branch
Copy icon
For example, if you wanted to see the commits of a branch named primeagen from a remote named origin you would run:

git log origin/primeagen
Copy icon
Assignment
Run git log on the remote webflyx repo's update_dune branch using the --oneline flag. Do it from within the webflyx-local repo. You should see commits "A" through "I".
