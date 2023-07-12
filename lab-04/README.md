Sure, let's add some more steps to the process, which will give you a more comprehensive experience with syncing local and cloud repositories.

## 🔄 Lab 04 - Sync Local and Cloud Repositories

### Step 1: Checking the Status of Your Repository

Start by checking the current status of your repository.

1. Open VS Code and navigate to the Source Control panel in the Activity Bar.
2. Here you will see a summary of changes that have been made in your local repository, including any staged changes, unstaged changes, and untracked files.

This step is crucial to understand what changes you have made locally that could be committed and pushed to the remote repository.

**Q: What does the Git status show?**

A:
1. The version of Git you are using.
2. Your commit history.
3. The changes in your repository that have not yet been committed.
4. The contents of your files.

### Step 2: Staging Changes

Before you commit changes, you have to stage them.

1. In the Source Control panel, you can see a list of changes.
2. Click on the "+" button next to each change to add it to the staging area.

Staging allows you to select specific changes that you want to commit.

**Q: What does staging a file in Git mean?**

A: 
1. It commits the file.
2. It pushes the file to the remote repository.
3. It prepares the file for commit.
4. It deletes the file.

### Step 3: Committing Changes

Once your changes are staged, you can commit them.

1. Write a descriptive message for your commit in the text box at the top of the Source Control panel.
2. Click the checkmark above the text box to commit the changes.

Commits are like saving a version of your files. Every commit is a snapshot of your work that you can revert to if needed.

**Q: What is a commit in Git?**

A:
1. A saved version of your work.
2. A command to push your changes to the remote repository.
3. A clone of the remote repository.
4. A tool to resolve merge conflicts.

### Step 4: Pulling Changes from the Remote Repository

Now let's make sure you have the latest version of the codebase.

1. Click on the ellipsis (...) for more actions in the Source Control panel.
2. From the dropdown menu, select "Pull."

**Q: Why is pulling from the remote repository important?**

A: 
1. It changes the name of your repository.
2. It deletes files from your repository.
3. It ensures your local repository is up-to-date with the latest changes from the remote repository.
4. It makes your repository public.

### Step 5: Merging Changes Between Branches

Let's merge changes between branches:

1. In the Source Control section, click on the branch name.
2. A list of branches will appear. Right-click on the branch you want to merge into the current branch.
3. Select "Merge Branch."

**Q: Why would you merge branches in Git?**

A: 
1. To change the name of a branch.
2. To delete a branch.
3. To bring changes from one branch into another.
4. To create a new branch.

### Step 6: Pushing Local Changes to the Remote Repository

Finally, let's share our changes with others:

1. Find the "Synchronize Changes" button in the Status Bar of VS Code.
2. Click on this button. This will push your commits to the remote repository in Azure DevOps.

**Q: What does "pushing" to a remote repository do?**

A: 
1. It downloads the changes from the remote repository.
2. It deletes your local changes.
3. It uploads your commits from your local repository to the remote repository.
4. It creates a new remote repository.

### Step 7: Creating a New Branch

Branching allows you to isolate your work from the main project. Let's create a new branch:

1. In the Source Control panel, click on the current branch name.
2. Click on "Create new branch" at the top.
3. Enter a name for your branch and hit 'Enter'.

This creates a new branch where you can work independently without affecting the main project.

**Q: What is the main purpose of creating a new branch in Git?**

A:
1. To save changes to the remote repository.
2. To create a copy of the repository.
3. To isolate work on a specific task without affecting the main project.
4. To delete parts of the project.

### Step 8: Switching Between Branches

You can easily switch between different branches in your project.

1. Click on the current branch name in the Source Control panel.
2. Select the branch you want to switch to.

Remember, changes made in one branch do not affect other branches.

**Q: What happens when you switch branches in Git?**

A:
1. The previous branch is deleted.
2. Your changes are automatically pushed to the remote repository.
3. The files and directories in your workspace are updated to reflect the contents of the new branch.
4. Your local repository is reset.

### Step 9: Resolving Merge Conflicts

When merging branches, you may encounter conflicts. Let's see how to resolve them:

1. If a conflict occurs, VS Code will highlight the conflict in the text editor.
2. You can choose to accept the current change, accept the incoming change, or accept both changes.
3. Once you've resolved the conflict, you can stage and commit the changes.

Merge conflicts occur when the same part of your code is modified in two different branches.

**Q: What is a merge conflict in Git?**

A: 
1. A tool for merging branches.
2. An error that occurs when you try to commit changes.
3. An issue that arises when the same part of the code has been modified in two branches.
4. A tool for reverting to a previous commit.

### Step 10: Deleting a Branch

Once you have merged a feature branch into the main branch, you can delete the feature branch.

1. Click on the current branch name in the Source Control panel.
2. Right-click on the branch you want to delete.
3. Select 'Delete branch'.

Remember, it's a good practice to clean up branches that you are no longer using.

**Q: Why would you delete a branch in Git?**

A:
1. To delete the changes made in that branch.
2. To create a new branch.
3. To merge two branches.
4. To clean up after a feature has been merged into the main project.

---

By completing this lab, you've learned how to check the status of your repository, stage and commit changes, pull the latest updates from the remote repository, merge branches, and push local changes to the remote repository. These skills are crucial for effective collaboration using Git, VS Code, and Azure DevOps.
