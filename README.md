# git-training
A simple 101 on how to use Git

# Git Training Ideas

Set up a Github account (should probably just start off with accounts outside TMG GitHub, they can be added to TMG Github later as and when they need to use it)
Get Git for Windows (a lot of them use Windows)
I chatted to Greg about Git for Windows, and he quite rightly pointed out that this could be an issue, so we’ll need to give Greg a list of people who want to attend who are using windows so we can get Git installed for them. Macs have git installed natively
$ git config --global user.name "Your Name Comes Here"
$ git config --global user.email you@yourdomain.example.com
Create a repo
Clone it
Add some files locally
Git add . to track them
Commit with a commit message
Push
Look on Github and see the changes and the commit message
Make another change, commit and push it
Get someone else to do a change, do a git pull
See the changes on Github


.gitignore file
DON’T put credentials or sensitive data in git/source control!


# Make a new branch locally
Push it and add it to the remote
Make some changes, commit and push it
See the result on github


# Checkout the original master branch
Verify that the files are the same as the original branch and don’t have the changes in the new branch


# Do a merge request for the new branch, to merge it to master
View the merge request in Github and the diff
Merge it on Github
See the result


# Show an example of a merge conflict and how to resolve it (advanced and probably not required for Ops team tbh)


# Rough overview of Github settings - ensure repos are private and NOT public
Other elements of good practice - informative commit messages, README files etc.
Don’t put large files in git (images, blobs, large executables etc)
Don’t force push unless you know what you’re doing + be careful when rewriting history, ie avoid it completely unless you’re stripping blobs/credentials


Teach GitFlow

# Commands we need to teach:
git clone
git add
git commit
git push
git pull
git checkout
git status


# Possibly also (but I think unnecessary):
git log
git revert
git reset


I suggest to add the following topics to the list above:
Tagging/Releases
Rebase vs Merge
Pull Requests
Moving across commits/tags
Cherry picking
Blame
Diff

# Exercise 1

Sign up for a Github account
Clone the exercise repo <URL here>
Find a place you want the directory to be on your local machine eg mkdir ~/repos/
cd ~/repos
git clone <url>


