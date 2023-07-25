## Steps 

### Step 1: Exploring VS Code

The instructions remain the same as before. Familiarize yourself with Visual Studio Code's interface.

### Step 2: Install and Configure Git

![alt text](1.png)

While you still need to install Git from the terminal or your system's command line, you can configure your Git identity from VS Code's GUI
After initializing your Git repository, let's add a new file:

In VS Code, go to the Explorer pane.
Select the directory of your local Git repository (It should be open if you followed the previous steps).
Click on the 'New File' icon at the top of the Explorer pane.
Name the file 'README.md'.
Double click the new file in the Explorer to open it.
Add some content to your file, for example: # Welcome to My First Git Repository
Save the file by pressing Ctrl + S or by going to File > Save.
Now, you have a new file in your local Git repository, which we'll use in the subsequent labs to demonstrate various Git operations.

### Step 3: Initialize Your First Local Git Repository

In VS Code:

1. Open the Command Palette with `Ctrl + Shift + P` or by going to View > Command Palette.
2. Type `Git: Initialize Repository`.
3. Select the directory where you want your repository to be.
4. A new pane titled 'Source Control' should appear on the left, confirming that your local Git repository is ready.

### Step 4: Link Your Local Repository with Your Azure DevOps Account

For this step, we will need to create a new repository on Azure DevOps and then clone it on your local machine. 

1. Visit your Azure DevOps portal and create a new Git repository under your project.

2. After the repository is created, click on the "Clone" button in the upper right corner, and copy the repository's URL.

3. Now, go back to VS Code.

4. Click on the 'Clone Repository' button in the Source Control view or use the `Ctrl + Shift + P` command and type `Git: Clone`.

5. Paste the URL of the repository you copied earlier.

6. Choose a directory on your local machine where you want the cloned repository to be placed.

VS Code will clone the repository from Azure DevOps and open it for you. Your local Git repository is now linked to your Azure DevOps repository.

## Conclusion

Congratulations on setting up your VS Code and Git environment with Azure DevOps! You have configured Git, initialized a local repository, and linked it with Azure DevOps, all from within VS Code's GUI. In the next lab, we'll delve deeper into the Azure DevOps integration with VS Code. Great work and see you in the next lab!
