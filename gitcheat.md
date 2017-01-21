#GitCheatsheet
*Erin Siodmak*
Jan 17, 2017

credential.helper=osxkeychain [usual]
user.email=erin.siodmak@gmail.com
user.name=erinsiodmak

git config --global user.name "[name]

git config --global user.email [email address]

git config --list

git init

git remote add origin [URL of your remote repo]

git remote -v


--

#Commands we learned Day 1:

git config --global user.name "[name]" (how to configure your machine with git)

git config --global user.email "[email address]" (same as above but for email)

git config --list (lists status of git connection/account)

git init (still not sure... initializes git in a specific location on the local drive?)

git remote add origin [URL of your remote repository, ie on github]

git remote -v 

git status (tells status of files or repositories being staged or committed)

git log

git add . (stages files)

git commit -m "[clear message describing the changes you made]"

git push origin master (not sure what this means)

git reset (unstages a file)
use "git reset HEAD <file>..." to unstage (from cmd line git response)

add is like setting up a stage for something to be pushed later, commit is more like save/snapshot, and push sends it to github. multiple commits are like multiple versions.

git checkout -1 (to get the last or previous commit/repository version)

----

#Day 2

git clone [url for git repository] to create a clone/save a repository to local machine

is it a good idea to call folders something with _Repo to keep track of what you're using as a git repository? how can i tell? because the name doesn't necessarily match the folder name on my machine ?

http://stackoverflow.com/questions/24290358/remove-a-folder-from-git-tracking
for removing stuff


