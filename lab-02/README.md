# Lab 02 - Basic Git Operations

Welcome to Lab 02 of the "Git in Gear" workshop! Now that you've set up your environment and created a new file in your local repository, it's time to learn about the most fundamental Git operations: staging, committing, and pushing changes. All these operations will be performed using the VS Code's interface.

## Objectives 

1. Stage changes in your local Git repository.
2. Commit changes to your local Git repository.
3. Push changes from your local repository to your Azure DevOps repository.

## Prerequisites

Before we start, make sure you have:

1. A local Git repository linked to your Azure DevOps account.
2. A file in your local repository with some content (we created a README.md file in Lab 01).

## Steps 

### Step 1: Stage Your Changes

Staging is the step before committing. It's the process where you add changes to a new commit. In our case, we will stage the README.md file that we created in the previous lab.

1. Open the Source Control pane in VS Code (the icon that looks like a branch on the left sidebar).
2. You should see README.md under Changes. This indicates that this file has been changed but not yet staged.
3. Click on the '+' button next to README.md to stage your changes.

Q: What is the purpose of the staging area in Git?

A:

1. It tracks all the files and changes that are about to be committed.
2. It compiles the project's source code.
3. It shows the history of all commits made.
4. It checks the status of your repository.

### Step 2: Commit Your Changes

Committing is the process of saving your changes to the local repository.

1. In the Source Control pane, you should see a text box at the top where you can enter a commit message.
2. Write a short, descriptive message about what changes were made. For example: "Add initial content to README.md".
3. Press `Ctrl + Enter` or click the ✔️ button to commit the changes.

Q: What information should a good commit message include?

1. The weather forecast for the day.
2. The time the changes were made.
3. The reason for the changes and a description of the changes.
4. The list of files that are about to be committed.

### Step 3: Push Your Changes to Azure DevOps

Pushing refers to sending your committed changes to a remote repository. In our case, we will push our commit to our Azure DevOps repository.

1. Go to the bottom-left corner of VS Code, click on the cloud upload icon or the 'Synchronize Changes' text.
2. In the dialog that appears, confirm the action.

VS Code will then push your changes to your Azure DevOps repository.

Q: What does the "push" operation do in Git?

1. It downloads changes from the remote repository to your local repository.
2. It uploads your commit(s) from your local repository to a remote repository.
3. It changes the current working directory.
4. It combines the changes from different branches.

### Step 4: Pull Changes from Azure DevOps

Pulling refers to fetching changes from a remote repository and merging them into your current working branch.

1. Go to the bottom-left corner of VS Code, click on the 'Synchronize Changes' text or the circular arrows icon.
2. In the dialog that appears, confirm the action.

VS Code will then pull any changes from your Azure DevOps repository and merge them into your local repository.

Q: Why is "pulling" important in a team environment?

1. It lets you work on your own without any disturbances.
2. It ensures that your local repository is always up to date with the latest changes in the remote repository.
3. It prevents you from committing changes to your repository.
4. It deletes unwanted changes from your repository.

### Step 5: Checking the Status of Your Repository

You can use VS Code's Source Control pane to see the status of your repository.

1. Click on the Source Control icon in the left sidebar.
2. Here, you can see which files have been changed, staged, or are untracked.

Q: What information does the status of a Git repository provide?

A:

1. The email address of the repository owner.
2. The differences between the working directory and the staging area, including which files have changes that are staged, which files have changes that aren't yet staged, and which files aren't being tracked by Git.
3. The list of all collaborators in the project.
4. The size of the repository.

### Step 6: Viewing Commit History

VS Code allows you to view the commit history directly from its interface:

1. Open the Command Palette with `Ctrl + Shift + P`.
2. Type `Git: Show History`.
3. Press `Enter`.

A new tab will open in VS Code, showing the commit history of the current repository.

Q: What information can you find in a Git commit history?

1. The name of the creator of Git.
2. The color scheme of your Git terminal.
3. The author, date and time, and a brief description of each commit.
4. The list of all files in the repository.

### Step 7: Create a New Branch

Branching in Git is a way to work on different versions of a repository at one time. Let's create a new branch in VS Code:

1. Go to the bottom-left corner of VS Code where you see the name of your current branch (likely `master` or `main`).
2. Click on it and type the name of your new branch in the input field (for example, `feature`).
3. Press `Enter`.

VS Code will create a new branch and automatically switch to it.

Q: Why would you create a new branch in Git?

1. To delete the changes made in the main branch.
2. To isolate a set of changes from the main line of development.
3. To rename the main branch.
4. To synchronize the local repository with the remote repository.

## Conclusion

Excellent job! You've successfully performed the basic Git operations: staging, committing, and pushing changes—all from within VS Code's GUI. You've made changes to a file, committed those changes to your local repository, and then pushed them to your Azure DevOps repository. In the next lab, we'll dive deeper into Azure DevOps and its integration with Git and VS Code. Keep up the good work!
