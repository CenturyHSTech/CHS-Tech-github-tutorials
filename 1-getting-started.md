# Getting Started

In this tutorial, we'll cover the following topics:

1. Creating a GitHub account
2. Installing and configuring Git

## Creating a GitHub Account

To create your GitHub account:

1. Go to https://github.com and click "Sign up".
2. Enter the requested information
   - Make sure to choose an appropriate username, as others will be able to see it and it will show up in GitHub next to files you edit.
3. Click "Create Account"
4. Answer the interest questions or scroll down and click "Complete Setup"
   - A verification email will be sent to the email address you entered in (2).
5. Check your email for the verification email and click "Verify email address".

## Installing and Configuring Git

1. Go to https://git-scm.com/downloads and click the correct download link for your Operating System.
2. (MacOS only) The recommended way to install Git, as of time of writing, is to install it via [Homebrew](https://brew.sh). The full instructions to install Git are:
   1. Open a Terminal window (this can be done by pressing Cmd+Space, then typing "terminal" into the search bar and presssing enter)
   2. Install Homebrew by pasting the command at [brew.sh](https://brew.sh) into your terminal window, then pressing enter.
   3. Install Git using homebrew by typing `brew install git` into your terminal window and pressing enter.
   - Leave your terminal window open, as you will use it in step 5.
3. (Windows only) Download and run the installer file to install Git.
4. (Windows only) Open the start menu and look for "Git Bash", then run it. This will open a bash shell (similar to a terminal or command prompt window) that we can use to run git commands.
5. Configure Git using your terminal (MacOS) or Git Bash (Windows) window.
   1. Type `git config --global user.name "Firstname Lastname"`, substituting in your name, and press enter.
   2. Type `git config --global user.email "my.email@example.com"`, substituting in your email address, and press enter.
   - These two commands will set the name and email to be associated with your git commits. The email should be the same as the one you used for GitHub.
6. You're done! Feel free to close your terminal or git bash window.
