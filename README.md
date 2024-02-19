Assignment: Basic Git and GitHub Workflow

Objective:
The objective of this assignment is to familiarize students with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

Requirements:

A GitHub account (create one if you don't have it already).
Git installed on your local machine.
A code editor of your choice (e.g., Visual Studio Code, Sublime Text).
Task 1: Repository Setup

GitHub Repository Creation:

Log in to your GitHub account.
Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").
Initialize it with a README file.
Task 2: Local Setup

Local Folder Setup:

Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").
Open a terminal or command prompt and navigate to the created folder.
Git Initialization:

Initialize a new Git repository in your local folder using the following command:
csharp
Copy code
git init
Connecting to GitHub:

Link your local repository to the GitHub repository you created in Task 1 using the following command:
csharp
Copy code
git remote add origin <repository-url>
Replace <repository-url> with the actual URL of your GitHub repository.
Task 3: Making Changes

Create a File:

Inside your local folder, create a new text file (e.g., hello.txt).
Add a simple text message (e.g., "Hello, Git!") to the file.
Committing Changes:

Stage the changes using the following command:
bash
Copy code
git add hello.txt
Commit the changes using the following command:
bash
Copy code
git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub

Pushing to GitHub:

Push the committed changes to your GitHub repository using the following command:
bash
Copy code
git push -u origin main
Task 5: Verification

Verify on GitHub:

Visit your GitHub repository in a web browser and confirm that the hello.txt file and commit message are visible.

