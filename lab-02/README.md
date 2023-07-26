# 🔀 Lab 02 - Basic Git Operations

Welcome to the second lab of our "Git in Gear" Workshop! This lab focuses on the fundamental operations in Git: staging, committing, and pushing changes. We will perform all these operations within the Visual Studio Code interface.

## Objective

This lab aims to:

- Understand the basic Git operations.
- Learn how to stage, commit, and push changes using Visual Studio Code.
- Sync your local Git repository with Azure DevOps.

## Requirements

- Completion of Lab 01 and successful setup of Visual Studio Code with Git.
- An active connection to the Azure DevOps repository.

## Tasks

### Task 1: Create a New File

1. In Visual Studio Code, navigate to your Git repository.
2. Click on `New File` icon in the Explorer view.
3. Name it `README.md` and write some basic content, such as `# My First Repository`.

### Task 2: Stage Your Changes

Staging is the process of preparing your changes for a commit. 

1. Click on the Source Control view in the activity bar.
2. You will see your `README.md` file listed as a change.
3. Click on the `+` icon next to the `README.md` file to stage your changes.

### Task 3: Commit Your Changes

Committing is the process of saving your changes to the local repository.

1. In the Source Control view, you will see a text box at the top under the "CHANGES" section.
2. Enter a commit message, like `Add README.md`, in this box.
3. Press `Ctrl+Enter` (or `Cmd+Enter` on Mac) or click the checkmark above the text box to commit your changes.

### Task 4: Push Your Changes to Azure DevOps

Pushing is the process of syncing your local repository with the remote repository.

1. Click on the `...` icon in the Source Control view.
2. From the drop-down menu, select `Push`.
3. If asked, select `origin` as the destination of the push.
4. Your changes are now pushed to Azure DevOps!

### Task 5: Verify Your Changes on Azure DevOps

1. Navigate to your Azure DevOps project in your web browser.
2. Go to 'Repos' > 'Files'.
3. You should see your `README.md` file with the content you added.

## Summary

In this lab, you've learned the basics of Git operations and how to perform them within Visual Studio Code. You created a new file, staged your changes, committed these changes to your local repository, and finally pushed them to Azure DevOps. You're making excellent progress! Next, we'll dive into how to integrate your local repository with Azure DevOps more deeply.

[Proceed to Lab 03 - Azure DevOps Repository Integration](./lab-03/README.md)
