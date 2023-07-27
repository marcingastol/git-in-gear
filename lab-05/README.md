# 📚 Lab 05 - Learning Git Log and Git Diff

Welcome to the fifth lab of our "Git in Gear" Workshop! In this lab, we will focus on understanding your repository's history. We'll explore the usage of `git log` to view commit history and `git diff` to compare changes between commits or branches.

## Objective

This lab aims to:

- Understand the purpose and usage of `git log` and `git diff`.
- Learn how to view commit history and compare changes between commits or branches using Visual Studio Code.

## Requirements

- Completion of previous labs and successful setup of Visual Studio Code with Git.
- An active connection to the Azure DevOps repository.

## Tasks

### Task 1: Viewing the Commit History with Git Log

Git log is a utility tool that allows you to view information about previous commits that have occurred in the project.

1. Open the Command Palette with `F1` or `Ctrl+Shift+P` on Windows and Linux, `Cmd+Shift+P` on Mac.
2. Type `Git: Show All Commits` and select it.
3. A new tab opens in Visual Studio Code showing a list of all commits, just like `git log` in the terminal.

### Task 2: Viewing Changes with Git Diff

Git diff is used to track changes between different commits and branches. Let's use it to see how our files have changed over time.

1. Select the Source Control view in the activity bar.
2. You'll see a list of all changes. Click on the file you want to inspect.
3. A new tab opens showing the differences between the current state of the file and the last commit.

### Task 3: Comparing Branches with Git Diff

You can also compare different branches using Git diff.

1. Open the Command Palette with `F1` or `Ctrl+Shift+P` on Windows and Linux, `Cmd+Shift+P` on Mac.
2. Type `Git: Compare...` and select it.
3. Select the two branches you want to compare. The changes between the branches will be displayed.

## Summary

In this lab, you've learned how to view the commit history and compare changes in your repository using `git log` and `git diff`. These commands are essential tools for understanding your project's history and identifying changes. Next, we'll dive into powerful Git commands that let you navigate and modify your project's history.
