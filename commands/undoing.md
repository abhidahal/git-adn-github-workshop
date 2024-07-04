# Undoing

## Undoing changes in your repo

*   **`git mv <existing_path> <new_path>`**

    \-Move (&/or rename) a file & stage move\

*   **`git rm <file>`**

    \-Remove a file from the working directory & staging area, then stage the removal\

*   &#x20;**`git rm --cached <file>`**

    \-Remove from staging area only\

*   **`git checkout <commit_ID>`**

    \-View a previous commit (READ only)\

*   **`git revert <commit_ID>`**

    \-Create a new commit, reverting the changes from a specified commit\

*   **`git reset <commit_ID>`**

    \-Go back to a previous commit & delete all commits ahead of it (revert is safer). Add --hard flag to also delete workspace changes (BE VERY CAREFUL)









