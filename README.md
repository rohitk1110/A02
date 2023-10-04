# A02
# Step 1: Install Git, WebStorm, and Set Up GitHub Account

## Install Git

https://git-scm.com/downloads

## Install WebStorm 

https://www.jetbrains.com/webstorm/download

## Create a GitHub Account

https://github.com

# Step 2: Configure Git

## Open Git Bash

Launch the command line interface on your computer.

## Configure Your Identity

### Set your name and email address for Git using the following commands, replacing "Your Name" and "your.email@example.com" with your actual information

git config --global user.name "Your Name"

git config --global user.email your.email@example.com

# Step 3: Create a Local Git Repository

## Create a Project Folder

Create a folder on your computer where you want to store your project.

## Open WebStorm

Launch WebStorm and open the project folder you just created.

## Initialize a Git Repository

In WebStorm, go to VCS > Import into Version Control > Create Git Repository.

Select your project folder and click "OK."

# Step 4: Create and Commit Changes

## Create a New File

In WebStorm, right click on your project folder, choose "New > File," and give it a name.

## Edit the File

Open the newly created file and make some changes.

## Stage and Commit Changes

In WebStorm, go to VCS > Git > Add to stage your changes.

Then, go to VCS > Commit to commit your changes. 

Add a commit message describing your changes and click "Commit."

# Step 5: Create a GitHub Repository

## Login to GitHub

Go to the GitHub website and log in to your account.

## Create a New Repository

Click the "+" sign in the upper right corner and select "New repository."

Fill in the repository name, a brief description, and other settings.

Click "Create repository."

# Step 6: Connect Local and Remote Repositories

## Add a Remote Origin

In WebStorm, go to VCS > Git > Remotes > Add > Origin.

Enter your GitHub repository's URL and click "OK."

## Push to GitHub

In WebStorm, go to VCS > Git > Push.

Select the branch you want to push (usually "main" or "master") and click "Push."

# Step 7: View Your Repository on GitHub

## Refresh Your GitHub Repository

Visit your GitHub repository in a web browser, and you should see your code and commit history.

# References

## Git Official Documentation

https://git-scm.com/doc

## GitHub Guides

https://docs.github.com/en

## WebStorm Documentation

https://www.jetbrains.com/webstorm/learn

## Glossary:
- **Branch**: A separate line of development in Git that allows you to work on a specific feature or bugfix without affecting the main code.

- **Clone**: Creating a copy of a Git repository on your local computer to work with.

- **Commit**: Saving changes in Git, creating a snapshot of the project at a specific point in time.

- **Fetch**: Downloading changes from a remote Git repository without making any changes to your local files.

- **GIT**: A version control system used for tracking changes in code and collaborating with others.

- **Github**: A web-based platform for hosting and collaborating on Git repositories.

- **Merge**: Combining changes from one branch into another branch to integrate new features or changes.

- **Merge Conflict**: When Git cannot automatically combine changes due to conflicting edits in the same part of a file.
  
- **Push**: Uploading your local Git commits to a remote repository, making them available to others.

- **Pull**: Fetching and merging changes from a remote repository into your local copy of a repository.

- **Remote**: A reference to a Git repository hosted on a server, typically used for collaboration.

- **Repository**: A directory or storage space where your project's files, history, and version control information are stored.
