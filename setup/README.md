# MacOS

git should be already installed on your Mac, if not you can download and install from here: https://git-scm.com/download/mac

Once you install it or if it's already installed, run the following command:

$ git --version

The output should be something similar to this:

git version 2.14.3 (Apple Git-98)

git works over ssh, so you will need to setup and ssh key to be able to use it.

Let's check if you already have a ssh key setup, run:

$ ls -al ~/.ssh/id_rsa*

The output should have at least the two following files:

.ssh/id_rsa
.ssh/id_rsa.pub

If you don't have the two files above, let's generate them:

$ ssh-keygen

Hit Enter three times and go with the defaults.

(
if you want to read more about SSH and keys, try this:
- https://wiki.archlinux.org/index.php/SSH_keys
- https://help.ubuntu.com/community/SSH/OpenSSH/Keys
)

# Windows

TODO

# setting up GitHub for both MacOs and Windows

1. Go to https://github.com/telegraph
- you will be able to see our public (open source) repositories
- P.S. Let us know if you see anything public that should not be :)

2. Click Sign Up or Login
- choose a username
- enter you telegraph email address for example
- choose a password

- if you already have a github account -> Login

3. Click on your avatar in to right hand corner -> Settings

4. Click SSH and GPG keys

5. New SSH key

6. Give the key a name

7. in your shell, run:

$ cat ~/.ssh/id_rsa.pub

8. Copy and Paste the output into the Key field in github

9. Click Add SSH key

All done, you are now setup to use git with GitHub over SSH.
