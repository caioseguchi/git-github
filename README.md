## git-github

🔥 Essential Git Commands for Git Bash


Creating a Git Repository and Pushing It to GitHub
🆕 Initialize a New Repository and Push It to GitHub
# Create a README.md file with a title
echo "# git-github" >> README.md

# Initialize the Git repository
git init

# Add the README.md file to the staging area
git add README.md

# Commit the changes with a message
git commit -m "First commit"

# Rename the default branch to 'main'
git branch -M main

# Add the remote repository (replace with your actual repository URL)
git remote add origin https://github.com/caioseguchi/git-github.git

# Push the local repository to GitHub
git push -u origin main


🔄 Push an Existing Repository to GitHub
If you already have a local Git repository and just need to link it to GitHub, use the following commands:

# Add the remote repository
git remote add origin https://github.com/caioseguchi/git-github.git

# Rename the default branch to 'main' (if needed)
git branch -M main

# Push the existing repository to GitHub
git push -u origin main
📌 Basic Commands
# Clear screen
clear

# List files and directories
ls

# Create a new directory
mkdir name-of-directory

# Enter a directory
cd name-of-directory/

# Print a message
echo hello

# Create a file
echo hello > hello.txt

# Remove a file
rm hello.txt

# Go back to the previous directory
cd ..

# Delete a directory
rm -r name-of-directory

📌 Git Push and Status

# Check the status of repository
git status

# Changes to the staging area
git add *

git commit -m "Describe what you are doing, e.g., Add new file"

git push origin main

📌 Git Branching
# Check the branch list
git branch

# Create a new branch
git branch new-branch-name

# Switch to the new branch
git checkout new-branch-name

# Create and switch to a new branch in one command
git checkout -b new-branch-name

# Delete a local branch
git branch -d branch-name

# Confirm you're in the correct branch
git branch

# Push the new branch to GitHub
git push -u origin new-branch-name


📌 Merging Branches
# Switch to the main branch
git checkout main

# Merge another branch into main
git merge branch-name

# Push changes to GitHub
git status
git add *
git commit -m "Merge"
git push origin main