# API-Documentation
API Documentation to simplify the development of backend and frontend

## Steps to create new branch

# Create a new branch
...........git branch feature-branch

# Switch to the new branch
...........git checkout feature-branch
Alternatively, you can combine these two commands using the -b option with git checkout:
# Create and switch to a new branch
...........git checkout -b feature-branch

2. Make Changes:
   Make the necessary changes to your code using your preferred code editor.

   3. Stage and Commit Changes:
      # Stage changes
..........git add .

# Commit changes
.........git commit -m "Add new feature"
4. Push Changes to the New Branch:
# Push changes to the new branch
.........git push origin feature-branch

This assumes that the branch feature-branch does not exist on the remote repository. If it already exists, you might want to pull the latest changes from the remote branch before pushing your changes:

# Pull changes from the remote branch
.........git pull origin feature-branch

# Push changes to the new branch
.......git push origin feature-branch
5. View Changes on the Remote Repository:
Go to your Git hosting provider (e.g., GitHub, GitLab, Bitbucket) and navigate to the repository.
You should see the new branch listed, and you can inspect the changes you pushed.
Notes:
Adjust the branch name (feature-branch) according to your naming conventions.
Make sure you are in the correct branch (feature-branch) before making changes and pushing.
Always pull changes from the remote branch before pushing if the branch already exists remotely to avoid conflicts.


