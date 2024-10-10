# Git-commands
A place to learn about different Git commands 

1. Creating a Repository
Steps:
a. Navigate to your desired directory.
b. Create a new Git repository.
c. Use the command "git init". This creates an empty Git repository in the specified directory. You can now track and manage your project's files.

2. Cloning a Repository
Steps:
a. Copy the repository URL from GitHub.
b. Clone the repository to your local machine.
c. With the command "git clone( copied URL)

3. Creating Branches
Steps:
a. Create a new branch to work on a feature without affecting the main branch.
b. Use "git checkout -b (branch name). This creates and switches to the new branch. 

4. Committing Changes
Steps:
a. Stage your changes.
b. Commit the staged changes.
c. Git add and git commit go hand in hand
   -git add
   -git coomit -m "commit message
Use meaningful commit messages to describe what you've changed.

5. Reverting Commits
Steps:
a. To revert the last commit, use the command below.
b. git revert (commit-hash). Replace (commit-hash) with the actual commit hash you wish to revert. This creates a new commit that undoes the changes from the specified commit.

6. Pulling and Pushing Changes
  a. Pull Changes (Downstream):
     -Fetch and merge changes from the remote repository to your local branch.
     -git pull origin (branch-name)

  b. Push Changes (Upstream):
     -Push your committed changes to the remote repository.
     -git push origin (branch-name)

7. Fetching Changes
Steps:
a. Fetch changes from the remote repository without merging them. "git fetch origin". This will retrieve updates from the remote repository without modifying your local files.

8. Merging Branches
Steps:
a. Switch to the branch where you want to merge another branch.
b. Merge the changes from another branch.
c. git checkout (branch-name). Switch to the branch you want to merge into.
d. git merge (branch to merge). Replace <branch-to-merge> with the name of the branch you wish to merge.

9. Renaming Branches
Steps:
a. Rename the current branch.
b. git branch -m (new branch name). This renames the current branch to the specified (new-branch-name).

10. Creating Pull Requests
Steps:
a. Push your changes to a remote branch.
b. Create a Pull Request (PR) from the GitHub repository.
Instructions:
a. Navigate to your GitHub repository.
b. Click on "Pull Requests."
c. Click on "New Pull Request" and choose the branch you'd like to merge into the main branch.

11. Reviewing and Merging Pull Requests
Steps:
a. Review the code changes in a Pull Request.
b. Approve and merge the Pull Request if everything is correct.
Instructions:
   -Open the Pull Request on GitHub.
   -Review the code changes and click "Merge Pull Request" to finalize the changes.

12. Reverting Pull Requests
Steps:
a. Use the GitHub UI to revert a merged Pull Request.
Instructions:
   -Navigate to the merged Pull Request on GitHub.
   -Click on the "Revert" button to create a new PR that undoes the changes made by the original PR.
How to Push This README.md to Your GitHub Repository
Steps:
1. Stage your README.md file.
2. Commit the changes.
3. Push the file to your GitHub repository.
   git add README.md
   git commit -m "Added detailed README.md"
   git push origin <branch-name>

