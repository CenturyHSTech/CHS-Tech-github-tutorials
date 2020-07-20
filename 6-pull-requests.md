# Github Workflow and Pull Requests

[<< Index](readme.md) [< Back](5-branching.md)

In this page we'll talk about the GitHub workflow that we recommend
your team use, or at least one like it. Within it, we will discuss creating a
**Pull Request**, and getting another member of your team to approve it.

## Recommended Workflow

1. Assign yourself the task on Trello
2. Create and checkout a new [branch](5-branching.md) for the task. Give this 
branch a descriptive name.
3. Write and test the code
4. Push your code to GitHub under your branch.
5. On github.com, at your repository page, click on "Pull Requests" and then click
"New Pull Request"
6. Set the base branch to `main` and the compare branch to the branch you created 
earlier.
7. Fix any [merge conflicts](4-merge-conflicts.md) that exist, if any. If not, 
GitHub will say that the branches can be automatically merged.
8. Get a different member of your team to look over the code.
    - They may have questions, notice a bug, or small suggestions to change.
    If they do, then implement those changes, commit them, and repeat step 8.
9. The other member, if no problems are found, can approve the pull request. This
will merge the code in your branch into `main`.
