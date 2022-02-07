## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an Open Source Distributed Version Control System

2. What is the difference between Git and GitHub?
Git is a revision control system, a tool to manage your source code history. GitHub is a hosting service for Git repositories.

3. Why do we create a branch?
We create a branch by typing git checkout -b "branch-name"

4. What is the purpose of a Pull Request?
It is a git command used to update the local version of a repository from a remote. So that way we can make changes without having to affect the main.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The git fetch command downloads commits, files, and refs from a remote repository into your local repo while the git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch and the git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content

7. What is a merge conflict?
Merge conflict occurs when your changes conflict (will need to overwrite what is on the remote repository, name it master or the branch where you pushing your changes onto) with another person of your team's changes (his changes since last time you pulled would overwrite your changes that you are trying to push, or you will overwrite his changes).

8. How do you resolve a merge conflict?
A. Accept the local version. To accept all changes on a file from the local version, run: git checkout --ours <Branch Name>
Alternatively, to accept the local version for all conflicting files, use: git merge --strategy-option ours
B. Accept the remote version. To update the changes on a file from the remote branch, run: git checkout --theirs <Branch Name>
Accept the remote version for all conflicting files with: git merge --strategy-option theirs
C. Review changes individually. The final option is to review each change separately. This option is also the best path to take, especially when working with multiple files and people. To make this job more manageable, use special tools to help review individual conflicts .
