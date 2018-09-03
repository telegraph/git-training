# Exercise 1 - Creating a Repository

## First Add your name and email to your local Git Config

    - `$ git config --global user.name "Your Name Comes Here"`
    - `$ git config --global user.email "you@yourdomain.example.com"`

## Let's create the repository in GitHub

1. Go to GitHub: http://github.com and login into your account
2. Click New repository on the left
3. Give it a name
4. You will have to use Public, please remember Public means everybody on the internet can see it :)
    - don't forget to delete it once done with all the exercises
5. Hit create

## Your repository is on git hub, let's get a copy on your laptop

1. Once created, switch the toggle to SSH and copy the SSH link
2. Run the following command in your shell:
    - ` $ git clone PASTE_THE_URL_HERE `

## Now that you have a copy, let's create a README file and see if we can get it on GitHub

1. Change directory to inside the repository
    - ` $ cd NAME_OF_THE_REPO_HERE `
2. create a README file 
    - ` $ echo "Hello world" > README`
3. Add the new file to git (tell git to start tracking it)
    - ` $ git add README`
4. Commit this version of the README file to git
    - ` $ git commit --message "My first commit of the README file"`
5. Push your changes to Github
    - ` $ git push `
6. Go to github in your browser and see if your README is there

## Ask a friend to push some changes to your repo.

1. Ask them to clone your repo
   - ` $ git clone PASTE_THE_URL_HERE `
2. Change directory to inside the repository
   - ` $ cd NAME_OF_THE_REPO_HERE `
3. Ask them to change your file, and add a new line and perhaps delete or edit the line you added too
4. Ask them to commit this version of the README file to git
    - ` $ git commit --message "My commit to YOUR_NAME_HERE's README file"`
5. Ask them to push their changes to Github
    - ` $ git push `
6. Go to github and in your browser and view the changes they have made. If you click on the commit, you will be able to see the lines they added in green and any lines they changed or deleted in red. Changing the text in a line will be shown as a deletion of the line, with the new text as a new line in green.

Congratulations! You have successfully made a repository in GitHub, added a file, committed your changes locally and pushed them to GitHub :)

Lets move on to exercise two where we'll explore some of the other features of Git and how to use it