# A02 - Git, GitHub, and WebStorm Tutorial

## Introduction

This tutorial explains how to use Git, GitHub, and WebStorm. It is designed for beginners and provides step-by-step instructions for setting up the programs, creating a GitHub repository, cloning a repository into WebStorm, making changes, committing those changes, and pushing them to GitHub.

---

# Part 1: Directions for Using Git, GitHub, and WebStorm

## Step 1: Create a GitHub Account

1. Go to https://github.com/
2. Click **Sign Up**.
3. Enter your email address.
4. Create a password and username.
5. Verify your email address.
6. Sign in to your GitHub account.

## Step 2: Install Git

1. Go to https://git-scm.com/downloads
2. Select your operating system.
3. Download Git.
4. Open the installer.
5. Follow the installation instructions.
6. Finish the installation.

To check that Git was installed correctly, open a terminal and type:

git --version

## Step 3: Install WebStorm

1. Go to https://www.jetbrains.com/webstorm/download/
2. Download WebStorm for your operating system.
3. Open the installer.
4. Follow the installation instructions.
5. Open WebStorm after the installation is complete.

## Step 4: Connect Git to WebStorm

1. Open WebStorm.
2. Open Settings.
3. Go to Version Control > Git.
4. Make sure WebStorm detects the Git installation.
5. Click **Test**.
6. Click **Apply** and then **OK**.

## Step 5: Connect GitHub to WebStorm

1. Open WebStorm Settings.
2. Go to Version Control > GitHub.
3. Click the **+** button.
4. Select **Log In via GitHub**.
5. Sign in to your GitHub account.
6. Authorize WebStorm to access GitHub.
7. Return to WebStorm.

## Step 6: Create the A02 Repository

1. Sign in to GitHub.
2. Click the **+** button.
3. Select **New repository**.
4. Enter the repository name exactly as:

A02

5. Make sure the "A" is capitalized.
6. Select **Public**.
7. Select **Add a README file**.
8. Click **Create repository**.

Your repository URL should look like:

https://github.com/yourUCID/A02

## Step 7: Clone the Repository into WebStorm

1. Open the A02 repository on GitHub.
2. Click the **Code** button.
3. Copy the HTTPS repository URL.
4. Open WebStorm.
5. Select **Get from Version Control**.
6. Paste the repository URL.
7. Select where you want to save the project.
8. Click **Clone**.
9. Wait for WebStorm to open the project.

## Step 8: Edit README.md

1. Find README.md in the Project panel.
2. Double-click README.md.
3. Add or edit your tutorial.
4. Save your changes.

## Step 9: Commit Your Changes

1. Open the Commit window in WebStorm.
2. Select README.md.
3. Review your changes.
4. Enter a meaningful commit message.

Example:

Task: Create Repository

5. Click **Commit**.

Other good commit messages include:

Feature: added workflow for using GitHub

Feature: added WebStorm setup instructions

Feature: added glossary definitions

Fix: changed README.md for definition of terms

## Step 10: Push Your Changes to GitHub

1. Go to Git > Push.
2. Review the commit.
3. Click **Push**.
4. Open your A02 repository on GitHub.
5. Refresh the page.
6. Make sure your README changes appear.

## Step 11: Fetch and Pull Changes

Fetch checks for changes from the remote GitHub repository without automatically combining them with your current work.

Example command:

git fetch origin

Pull downloads remote changes and integrates them into your local project.

Example command:

git pull origin main

## Step 12: Create a Branch

1. Open the Git branch menu in WebStorm.
2. Select **New Branch**.
3. Give the branch a name, such as:

tutorial-update

4. Make your changes.
5. Commit the changes.
6. Push the branch to GitHub.

## Step 13: Merge a Branch

1. Switch back to the main branch.
2. Open the Git branch menu.
3. Select the branch you want to merge.
4. Select **Merge into Current**.
5. Review the changes.
6. Push the updated main branch to GitHub.

## Step 14: Resolve a Merge Conflict

A merge conflict can happen when two branches change the same part of a file.

If a merge conflict happens:

1. Open the conflicting file.
2. Review both versions.
3. Decide which changes should remain.
4. Edit the file to contain the correct final version.
5. Mark the conflict as resolved.
6. Commit the resolved file.

Example commit message:

Fix: resolved README merge conflict

7. Push the changes to GitHub.

---

# Part 2: Glossary

- **Branch** – An independent line of development that allows you to work on changes without immediately changing the main version of the project.

- **Clone** – A local copy of a remote repository downloaded to your computer.

- **Commit** – A saved snapshot of changes made to files in a Git repository.

- **Fetch** – Downloads information about changes from a remote repository without automatically merging them into your current branch.

- **GIT** – A distributed version control system used to track changes to files and source code.

- **Github** – An online platform used to host Git repositories and collaborate on software projects.

- **Merge** – The process of combining changes from one branch with another branch.

- **Merge Conflict** – A situation where Git cannot automatically combine changes because conflicting changes were made to the same content.

- **Push** – Sends commits from your local repository to a remote repository such as GitHub.

- **Pull** – Retrieves changes from a remote repository and integrates them into your local repository.

- **Remote** – A version of a repository stored somewhere other than your local computer, such as on GitHub.

- **Repository** – A project managed by Git that contains project files and the history of changes made to those files.

---

# References

GitHub Docs. https://docs.github.com/

Git Downloads. https://git-scm.com/downloads

JetBrains WebStorm Documentation. https://www.jetbrains.com/help/webstorm/

WebStorm Download. https://www.jetbrains.com/webstorm/download/
