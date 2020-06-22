# Creating a Git Repository

In this tutorial, we'll cover the following topics:

1. Creating a repository on GitHub
2. Cloning the repository to your computer

Please make sure to follow along, as we will ask you to share this repository with us in the next tutorial.

## Creating a Repository on GitHub

**Repositories** are the way to denote projects in Git. A repository contains files which are changed by **commits**. We will explore how to commit changes to a repository in a later tutorial.

To create a repository:

1. Visit https://github.com from your computer and login to your account if you have not already logged in.
2. Click the + icon in the top right of the window and click "New Repository"
3. Give your repository a name like `nwapw-test-repo` and make sure it is set to "Public"
4. For the purposes of this tutorial, check the "Initialize this repository with a README".
5. Click "Create repository".

## Cloning a Repository to your Computer

**Cloning** a repository is how we make a local copy of a repository and all the code that lives inside it. We can work on our local copy, making changes to the code and adding features, and then we can **commit** and **push** the changes to GitHub when we are happy with them. We will talk more about committing and pushing changes in a later tutorial.

1. Open a terminal or git bash window as you did in Tutorial 1.
2. Choose or make a folder on your computer that you will keep your NWAPW work in.
3. Change your terminal's current directory to this folder by running `cd path/to/folder`, substituting in your
   - For example, if I wanted to put my work in a "NWAPW" folder in "My Documents", I would type in `cd "My Documents/NWAPW"`
   - Make sure to put double quotes around your folder path if it has spaces in it.
4. Run `git clone git@github.com:github_username/repository_name.git`, substituting in your github username and the repository name you chose.
5. This will make a copy of the repository as it exists on GitHub in the folder you chose. For example, if my repository was named "nwapw-repo", and I used the same folder as in the last example, it would make a copy of the repository in "My Documents/NWAPW/nwapw-repo".
