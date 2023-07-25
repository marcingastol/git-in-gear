## Steps 

### Step 1: Install VS Code


### Step 2: Install and Configure Git

![alt text](1.png)
![alt text](2.png)
![alt text](3.png)
![alt text](4.png)
![alt text](5.png)
![alt text](6.png)
![alt text](7.png)
![alt text](8.png)
![alt text](9.png)
![alt text](10.png)
![alt text](11.png)
![alt text](12.png)
![alt text](13.png)
![alt text](14.png)
![alt text](15.png)
![alt text](16.png)
![alt text](17.png)
![alt text](18.png)
![alt text](19.png)
![alt text](20.png)
![alt text](21.png)

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
