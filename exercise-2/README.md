# Exercise 2 - Working with Branches

1. Make a new branch locally
   - ` $ git checkout -b NAME_OF_YOUR_BRANCH_HERE `
2. Push it and add it to the remote
   - ` $ git commit --message "Added new branch NAME_OF_YOUR_BRANCH_HERE"`
   - ` $ git push `
3. Make some changes, commit and push it
   - ` $ touch SOME_NEW_RANDOM_FILE `
   - ` $ git add . `
   - ` $ git commit --message "Added new file SOME_NEW_RANDOM_FILE`
   - ` $ git push `
4. See the result on github
5. Checkout the original master branch
   - ` $ git checkout master `
6. Verify that the files are the same as the original branch and don’t have the changes in the new branch
   - ` $ ls `
   The new file you added in step 3 should not be there anymore
7. Checkout the new branch again, and the new file you added should be there
   - ` $ git checkout NAME_OF_YOUR_BRANCH_HERE `
   - ` $ ls `
8. Do a merge request for the new branch, to merge it to master. This is done in Github.
9. View the merge request in Github and the diff
10. Merge it on Github
11. See the result on Github
12. Do a git pull and see the changes locally
   - ` $ git checkout master `
   - ` $ git pull `
   - ` $ ls `   

13. If we've time, I may show you an example of a merge conflict and how to resolve it (advanced and probably not required for Ops team tbh)

14. An important file in any repo is the .gitignore file. This allows you to have files that are not tracked by Git. So things you may wish to use locally that you don't want to end up on Github. Credentials, keys and passwords are a great example of this. Add names of files you want to ignore, using a newline for each.
DON’T put credentials or sensitive data in git/source control! Once they are there, they are very difficult to get rid of again, the history of the entire repo has to be rewritten, which is a royal pita! Other things you don't want in Git repos are large binary files - eg images, videos and other media. Bin files, Zip files and the like.