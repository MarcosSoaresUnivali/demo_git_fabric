# Power BI Version Control with Git, GitHub, Fabric and Azure

This example demonstrates how to use Git and GitHub to version control Power BI files **New (`.pbip`)** and manage them in GitHub, Fabric and Azure repositories.

## Prerequisites

- Git installed on your local machine
- A GitHub account
- Power BI Desktop installed
- Azure DevOps integration

## Steps

1. **Initialize a Git Repository**

   Open your terminal and navigate to your project directory. Initialize a new Git repository:

   ```sh
   git init

2. **Add Power BI Files**

    Add your Power BI project files (.pbip) to the repository:

    ```sh 
    git add *.pbip


3. **Commit Changes**

    Commit the added files to the repository:
    ```sh
    git commit -m "Initial commit of Power BI project files"


4. **Create a GitHub Repository**

    Go to GitHub and create a new repository. Follow the instructions to push your local repository to GitHub:

    ```sh
    git remote add origin https://github.com/yourusername/your-repo-name.git
    git branch -M main
    git push -u origin main


5. **Version Control**

    As you make changes to your Power BI files, use Git to track and commit those changes:

    ```sh 
    git add *.pbip
    git commit -m "Updated Power BI report"
    git push


6. **Collaborate**

    Use GitHub to collaborate with others. Create branches, open pull requests, and review changes to manage your Power BI project effectively.


## Conclusion

By following these steps, you can efficiently version control your Power BI files using Git and GitHub, ensuring a collaborative and organized workflow. ```
