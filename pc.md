## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? A command line version control system that stores commits of code at certain points in a project, and allows branching to occur.  
2. What is the difference between Git and GitHub?  Git keeps track of all the commits of code and gitHub is a more like a cloud storage to store the repository that keeps track of the branches.  
3. Why do we create a branch? We create a branch to work on the same project as others, without affecting the main branch of a project. 
4. What is the purpose of a Pull Request? A pull request lets you compare new changes to old changes from your branch to the main branch.   
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. git switch -c main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?  git fetch will not update any changes from the branch compared to a git pull which will update any changes made from the branch. A git pull is basically a git fetch and a git merge happening into whichever branch you are applying it to.  A git fetch compares the updated commit to the current branch.  A git pull updates the current branch with the updated commit. A git merge merges the updated commit with the branch.
7. What is a merge conflict? A merge conflict is when git can't automatically resolve problems between two commits. 
8. How do you resolve a merge conflict? You can open the file and manually make changes.  
