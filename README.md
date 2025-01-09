Git basic commands

//Commands for git initial for a project, creating a repository in github and pushing the file. Create a folder git-test (Open the folder in vs code and in terminal type the belows commands):

1. echo "# git-test" >> README.md
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin https://github.com/<username>/git-test.git
7. git push -u origin main

//To get the changes that were made directly in the README.md file on GitHub to reflect in your local repository, you need to pull the latest changes from the remote GitHub repository to your local one. Here's how to do it:

1. Ensure you are on the correct branch
    First, make sure you're on the main branch (or whatever branch you are working on) in your local repository. You can check this by running:
        git branch
    If you're not on the main branch, switch to it using:
        git checkout main
2. Fetch the latest changes from the remote repository
        git pull origin main