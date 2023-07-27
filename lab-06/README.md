# 🎯 Lab 06 - Git Reset, Revert and Checkout

Welcome to the sixth lab of our "Git in Gear" Workshop! This lab will provide hands-on experience with powerful Git commands that allow you to navigate your project's history and modify it when necessary. We'll cover `git reset`, `git revert`, and `git checkout`.

## Objective

This lab aims to:

- Understand the usage and implications of `git reset`, `git revert`, and `git checkout`.
- Learn how to undo changes and navigate through commits using Visual Studio Code.

## Requirements

- Completion of previous labs and successful setup of Visual Studio Code with Git.
- An active connection to the Azure DevOps repository.

## Tasks

### Task 1: Undoing Changes with Git Reset

`git reset` is used to discard commits in a private branch or reset your staging area. Let's practice with it.

1. Create a new file and commit it to the repository.
2. Open the Command Palette with `F1` or `Ctrl+Shift+P` on Windows and Linux, `Cmd+Shift+P` on Mac.
3. Type `Git: Undo Last Commit` and select it. The changes from the last commit have now been undone.

### Task 2: Reverting Commits with Git Revert

`git revert` is used to create a new commit that undoes the changes made in a previous commit. It's a safe way to undo changes, as it doesn't alter the existing commit history.

1. Go to the Source Control view.
2. Right-click on the commit you want to revert (from the list of commits under the `...` menu) and select `Revert Commit`.
3. A new commit is created with the opposite changes, effectively undoing the reverted commit.

### Task 3: Navigating through Commits with Git Checkout

`git checkout` allows you to navigate through the commits that have been made in the project, which can be useful when you need to return to a specific version of your project.

1. Go to the Source Control view.
2. Under the `...` menu, choose `Checkout to...`.
3. Select the commit you want to check out. Your project's state will now reflect the selected commit.

## Summary

In this lab, you've learned how to navigate your project's history and modify it using `git reset`, `git revert`, and `git checkout`. These commands provide a powerful way to undo changes and inspect previous versions of your project. In the next lab, we'll look at collaborative development using Git, including how to fetch and pull changes from remote repositories and resolve merge conflicts.

