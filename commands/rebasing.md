# Rebasing

Rebasing is the process of moving or combining a sequence of commits to a new base commit.

It is similar to merging but Rebasing replays changes from one line of work onto another in the order they were introduced, whereas merging takes the endpoints and merges them together.

## Rebasing a feature branch onto the main branch.

* **`git checkout feature`**\
  &#x20; &#x20;
* **`git rebase main`**

&#x20; &#x20;

### With tags

* **`git rebase -i (commit_ID)`**\
  **`-`**Interactively clean up a branch commit before rebasing onto the main.\

*   **`git rebase -i Head~n`**

    Interactively rebase the last n number of commits on the current branch.\
    n can be any number of last commits\
