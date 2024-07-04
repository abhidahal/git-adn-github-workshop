# Stashing

Stashing is when you want to record the current state of the working directory and the index, but want to go back to a clean working directory.

The command saves your local modifications away and reverts the working directory to match the `HEAD` commit.



*   **`git stash`**

    \-Store modified and staged changes.\

*   **`git stash save "comment"`**

    \-Store modified and staged changes with a comment.\

*   **`git stash list`**

    \-List all stash\

*   **`git stash apply`**

    \-Re-apply the stash without deleting it.\

*   **`git stash pop stash@{n}`** \
    \-Re-apply the stash at index n, then delete it from the stash list.

    &#x20;where n = index of stash.

    &#x20;omit stash@{n} to pop the most recent stash.\

*   **`git stash show stash@{n}`**

    \-Delete stash at index n

    &#x20;where n = index of stash\

*   **`git stash drop stash@{n}`**\
    \-Delete stash at index n.

    where n = index of stash

    omit stash@{n} to delete the most recent stash.\

*   **`git stash clear`**

    \-Delete all stashes.

