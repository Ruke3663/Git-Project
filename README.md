# Git-Project
Git commands that simulate a team building and releasing a product using the Gitflow workflow for this Project
![q](https://user-images.githubusercontent.com/61823039/221684906-40f39f5a-e037-4232-9d1b-fdace78f7e36.png)

mkdir finalassignment - Creates a new directory called "finalassignment".

cd finalassignment - Navigates to the "finalassignment" directory.

git init - Initializes a new Git repository in the current directory.

echo "Initial read me file" >> README.md - Creates a new file called "README.md" and adds the string "Initial read me file" to the file.

git add README.md - Adds the new file to the Git index.

git commit -m "add README.md" - Commits the changes to the Git repository with the commit message "add README.md".

git log --oneline --graph - Displays a graphical representation of the Git commit history.

git checkout -b develop - Creates a new branch called "develop" and switches to that branch.

touch fileA.txt - Creates a new file called "fileA.txt".

git add fileA.txt - Adds the new file to the Git index.

git commit -m "add fileA.txt" - Commits the changes to the Git repository with the commit message "add fileA.txt".

git log --oneline --graph - Displays a graphical representation of the Git commit history.

git checkout -b feature1 - Creates a new branch called "feature1" and switches to that branch.

echo "feature 1 wip" > fileA.txt - Overwrites the contents of the "fileA.txt" with the string "feature 1 wip".

git add fileA.txt - Adds the modified file to the Git index.

git commit -m "add feature 1 wip" - Commits the changes to the Git repository with the commit message "add feature 1 wip".

git log --oneline --graph - Displays a graphical representation of the Git commit history.

echo "feature 1 with 2 bugs" > fileA.txt - Overwrites the contents of the "fileA.txt" with the string "feature 1 with 2 bugs".

git add fileA.txt - Adds the modified file to the Git index.

git commit -m "add feature 1" - Commits the changes to the Git repository with the commit message "add feature 1".

git checkout develop - Switches to the "develop" branch.

git merge --no-ff feature1 - Merges the "feature1" branch into the "develop" branch with a non-fast-forward merge.

git branch -d feature1 - Deletes the "feature1" branch.

git checkout -b feature2 - Creates a new branch called "feature2" and switches to that branch.

echo "feature 2 wip" >> fileA.txt - Appends the string "feature 2 wip" to the end of the "fileA.txt".

git add fileA.txt - Adds the modified file to the Git index.

git commit -m "feature 2 wip" - Commits the changes to the Git repository with the commit message "feature 2 wip".

git checkout develop - Switches to the "develop" branch.

git checkout -b release1 - Creates a new branch called "release1"

