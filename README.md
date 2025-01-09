Git basic commands

//Commands for git initial for a project, creating a repository in github and pushing the file
Create a folder git-test (Open the folder in vs code and in terminal type the belows commands
echo "# git-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/<username>/git-test.git
git push -u origin main

