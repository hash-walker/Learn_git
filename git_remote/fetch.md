Fetch
Adding a remote to our Git repo does not mean that we automagically have all the contents of the remote. First, we need to fetch the contents (but not yet!).

Command
git fetch
Copy icon
This downloads copies of all the contents of the .git/objects directory (and other book-keeping information) from the remote repository into your current one.

Assignment
Before fetching the data itself, let's take a look at the new empty repo's .git/objects directory with find.

find .git/objects
Copy icon
It should be eerily empty with only 3 entries because we haven't fetched anything yet.

Making Fetch Happen
Now, to bring the remote webflyx repo's info into our webflyx-local repo, we have to fetch it.

Assignment
Run git fetch inside the webflyx-local repo.
Run find .git/objects to see all the new objects that were fetched!

Not Fetched
Just because we fetched all of the metadata from the remote webflyx repo doesn't mean we have all of the files.

Assignment
To demonstrate this, run git log inside the webflyx-local repo. You should see that you don't have any commits.

Run and submit the CLI tests from inside the new webflyx-local directory.


