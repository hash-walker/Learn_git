Undoing Changes
One of the major benefits of using Git is the ability to undo changes. There are a lot of different ways to do this, but first, we'll start by going back in the commit history without discarding changes.

Assignment
The new intern at Webflyx tried to add his favorite movie to the titles.md file, but overwrote the entire file by mistake!

To simulate that on the update_dune branch, go ahead and overwrite titles.md with this line: * The Internship
echo "* The Internship" > titles.md
Copy icon
Make sure the file is changed by running git status, then commit the changes. (Use a commit message starting with J:)
Run and submit the CLI tests.

Note: if you have disabled clobbering and get an error saying the file already exists, use the >| operator instead of > to forcibly truncate the file.
