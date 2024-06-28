# PLPBasicGitAssignment

Task 1: Repository Setup

GitHub Repository Creation:

Log in to your GitHub account.

Click on the "+" icon in the top right corner of the page and select "New repository".

Fill in the repository name (e.g., PLPBasicGitAssignment).

Optionally, provide a description.

Choose to make the repository public because it is going to be viewed by other party

Initialize the repository with a README file.

Click on "Create repository".


Task 2: Local Setup

Local Folder Setup:

Create a new folder on your local machine (e.g., PLPBasicGitAssignment).

Git Initialization:

Open a terminal or command prompt.

Navigate to the created folder using cd command.

cd path/to/PLPBasicGitAssignment

Initialize a new Git repository in your local folder.


git init

Connecting to GitHub:

Link your local repository to the GitHub repository you created in Task 1. Replace <repository-url> with your GitHub repository URL.


git remote add origin https://github.com/RamspheldOnyangoOchieng/PLPBasicGitAssignment.git

Task 3: Making Changes

Create a File:

Inside your local folder (PLPBasicGitAssignment), create a new text file. You can use your preferred text editor to create a file named hello.txt.

plaintext

hello.txt

Open a Text Editor like notepad using the command

notepad then click enter to open

Add a simple text message to hello.txt, for example:

PLP has really fed my Semester with Enjoyement.

Committing Changes:

Stage the changes to be committed.


git add hello.txt

Commit the changes with a descriptive message.


git commit -m "Add hello.txt with a greeting"

Task 4: Pushing to GitHub

Pushing to GitHub:

Push the committed changes from your local repository to your GitHub repository's main branch (or master branch if you haven't switched to the main branch).


git push -u origin main

If prompted, enter your GitHub credentials (username and password).

Task 5: Verification

Verify on GitHub:

Visit your GitHub repository in a web browser.

Navigate to the repository and confirm that the hello.txt file and your commit message are visible in the repository's file list and commit history.