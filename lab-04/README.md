# 🔄 Lab 02 - Understanding and Using Git Branches

Welcome to the third lab of our "Git in Gear" Workshop! In this lab, we will explore the power of branching in Git. By creating and managing different branches, you can work on different features in parallel without affecting the main codebase.

## Objective

This lab aims to:

- Understand the concept of Git branches.
- Learn how to create, switch to, and delete branches using Visual Studio Code.
- Understand the benefits of parallel development.

## Requirements

- Completion of previous labs and successful setup of Visual Studio Code with Git.
- An active connection to the Azure DevOps repository.

## Tasks

### Task 1: Create a New Branch

Branches are used in Git to isolate your work from the main codebase. Let's create a new branch for developing a new feature.

1. Click on the branch icon in the status bar at the bottom (it probably says `master` or `main`).
2. In the pop-up, select `Create new branch...`.
3. Name your new branch `feature-1` and hit `Enter`.

### Task 2: Switch Between Branches

Switching between branches is easy in Git, allowing you to hop between different lines of development quickly.

1. Click on the branch icon in the status bar again.
2. You'll see a list of all the branches. Select `master` or `main` to switch back to it.
3. Repeat the process to switch back to your `feature-1` branch.

### Task 3: Make Changes and Commit Them to the New Branch

Let's simulate working on a new feature by making changes in the `feature-1` branch.

1. Create a new file named `feature-1.txt` and write some content in it.
2. Stage and commit this change (recall from Lab 02).

### Task 4: Delete a Branch

Once you're done with a branch (for instance, after merging it), you might want to delete it.

1. First, switch back to the `master` or `main` branch.
2. Then, go to the Command Palette (`F1` or `Ctrl+Shift+P` on Windows and Linux, `Cmd+Shift+P` on Mac).
3. Type `Git: Delete Branch...` and select it.
4. From the list of branches, select `feature-1` to delete it.

## Summary

In this lab, you've learned the basics of branching in Git and how to manage branches within Visual Studio Code. You've created, switched to, and deleted branches. Additionally, you've made changes in a separate branch, simulating parallel development. You're making great strides in your Git journey! Up next, we'll explore how to understand your repository's history.

[Proceed to Lab 04 - Learning Git Log and Git Diff](./lab-04/README.md)
