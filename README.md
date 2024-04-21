# PLPBasicGitAssignment
Step 1: Repository Setup

1. GitHub Repository Creation:

  - Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").

  - Initialize it with a README file.



Step 2: Local Setup

2. Local Folder Setup:

  - Open a terminal or command prompt and navigate to PLPBasicGitAssignment.



3. Git Initialization:

  - Initialize a new Git repository in your local folder.



4. Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Step 1.

   ```

git remote add origin <https://github.com/Grace-Kabute/PLPBasicGitAssignment.git>

   ```

Step 3: Making Changes

5. Create a File:

  - Inside your local folder, create a new text file (e.g., `hello.txt`).

  - Add a simple text message (e.g., "Hello, Git!").



6. Committing Changes:

  - Stage the changes.

   ```bash

   git add hello.txt

   ```

  - Commit the changes.

   ```bash

   git commit -m "Add hello.txt with a greeting"

   ```



Step 4: Pushing to GitHub

7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin master

   ```