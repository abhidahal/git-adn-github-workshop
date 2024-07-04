# Synchronizing

## Synchronizing Local or/and Remote Repo

*   **`git remote add <alias> <url>`**

    \-Add a remote repo\

*   **`git remote`**

    \-View all remote connections. Add -v flag to view URLs.\

*   **`git remote remove`**

    \-Remove a connection\

*   **`git remote rename <old> <new>`**

    \-Rename a connection\

*   **`git fetch <alias>`**

    \-Fetch all branches from remote repo (no merge)\

*   **`git fetch <alias> <branch>`**

    \-Fetch a specific branch\

*   **`git pull`**

    \-Fetch the remote repo's copy of the current branch, then merge\

*   **`git pull --rebase <alias>`**

    \-Move (rebase) your local changes onto the top of new changes made to it the remote repo (for clean, linear history)\

*   **`git push <alias> <branch>`**

    \-Upload to a branch (can then pull request)&#x20;
