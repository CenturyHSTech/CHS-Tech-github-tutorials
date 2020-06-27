# Creating a Git Repository

[<< Index](readme.md) [< Back](2-creating-repository.md) | [Next >](4-merge-conflicts.md)

In this tutorial, we'll cover the following topics:

1. Making and commiting changes to a local repository.
2. Pushing the committed changes to GitHub.
3. Sharing your repository.

For this tutorial, we will continue using the repository we created in [the last tutorial](2-creating-repository.md). Please make sure to follow along, as we will ask you to share your repository with us at the end of this tutorial.

## Making and Commiting Changes

Any changes to a repository, including creating/removing files or editing a file, are collected into groups called **commits**. Commits are usually small and cover a single logical change, for example, "Added Subfeature X" or "Fixed off-by-one bug in collision detection logic".

For this tutorial, we want you to add a file to your project. For example, you could save a small text file with the content "Hello World!" into the folder your repository is in, alongside the readme file created by GitHub.

Once your file is created:

1. Open a git bash or terminal window.
2. Change directory into the folder your repository is in with `cd path/repository_name`
   - For example, `cd "My Documents/NWAPW/nwapw-repo"`.
3. Run `git add .`
   - This tells Git that it should prepare any changes you've made for committing. If you only want to commit changes to a specific file or files, you can do so by running `git add filename.ext`, substituting in the name of the file(s) you want to commit changes for.
4. Commit your changes with `git commit -m "Sample Commit"`.
   - The text in quotes is called a **commit message**. Commit messages are short descriptions of the changes you made in a commit, and are used by others on your team to quickly figure out what you did in a certain commit.
5. Leave your terminal window open, as we will use it in the next part of this tutorial.

## Pushing Commits to GitHub

Once you have committed your changes, they still only exist as a commit on your local machine. In order for those changes to show up on GitHub, you will need to **push** your changes.

To push your changes:

1. Using the terminal window you still have open, run `git pull`.
   - This command checks GitHub to see if anyone else has pushed a commit(s), and tries to merge your commit(s) onto theirs.
   - While this is not necessary right now since you are the only one to work on this repository, it will come in handy when you have a team during NWAPW.
2. Fix any merge conflicts, if there are any. You should not see any for the purposes of this tutorial, but you may encounter this during NWAPW. For more information on this, see [Merge Conflicts](4-merge-conflicts).
3. Run `git push`
4. Enter your github username and password into the prompt.
5. Once this is done, open up your repository in a web browser by visiting ht<span>tps://github.com/username/repository_n</span>ame
<!-- put the span block in the url so that it isn't hyperlinked -->

## Sharing Your Repository With Us

To make sure that everyone is ready for NWAPW, we ask that you share the repository you've used for this tutorial with us. To do so, just copy the link to your repository and paste it into the discord channel `#training-complete` with the message "Tutorial 3 complete".

[<< Index](readme.md) [< Back](2-creating-repository.md) | [Next >](4-merge-conflicts.md)
