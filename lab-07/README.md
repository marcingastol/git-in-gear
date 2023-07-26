# 🤝 Lab 07 - Collaborative Development Using Git

Welcome to the seventh lab of our "Git in Gear" Workshop! Here, we dive into the collaborative capabilities of Git. We'll cover fetching and pulling changes from remote repositories, as well as handling merge conflicts - an essential aspect of teamwork in software development.

## Objective

This lab aims to:

- Understand how to fetch and pull changes from a remote repository using Git and Visual Studio Code.
- Learn to handle and resolve merge conflicts.

## Requirements

- Completion of previous labs and successful setup of Visual Studio Code with Git.
- An active connection to the Azure DevOps repository.

## Tasks

### Task 1: Fetching Changes from a Remote Repository

Fetching allows you to see the changes that have been made in the remote repository without integrating them into your local repository.

1. Go to the Command Palette with `F1` or `Ctrl+Shift+P` on Windows and Linux, `Cmd+Shift+P` on Mac.
2. Type `Git: Fetch` and select it. This command fetches updates from the remote repository, but it does not merge them into your local repository.

### Task 2: Pulling Changes from a Remote Repository

Pulling changes from a remote repository allows you to update your local repository with the changes that have been made remotely.

1. Go to the Command Palette with `F1` or `Ctrl+Shift+P` on Windows and Linux, `Cmd+Shift+P` on Mac.
2. Type `Git: Pull` and select it. This command fetches and merges updates from the remote repository into your local repository.

### Task 3: Resolving Merge Conflicts

Merge conflicts occur when two branches have made changes to the same line in a file or when a file has been deleted in one branch but edited in the other. Resolving them is an essential part of collaborative work with Git.

1. Open a file with a merge conflict. You will see indicators showing the conflicting changes (`<<<<<<<`, `=======`, `>>>>>>>`).
2. Review the changes and decide whether to keep only your changes, only the other changes, or a combination of both.
3. Edit the file to resolve the conflict.
4. Save the file.
5. Stage and commit the file to mark the conflict as resolved.

## Summary

In this lab, you've gained a deeper understanding of how Git enables collaborative development. You've learned how to fetch and pull changes from remote repositories and to resolve merge conflicts, key skills when working on team projects. In the next lab, we'll look at the workflows that can help teams collaborate more effectively.
