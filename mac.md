## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
- Git is a version control system that keeps track of all the changes made to files in a
directory on our computer. The changes are saved in save slots that we call "commit." Git
also allows us to go through different versions of the files and compare them. Lastly, we can
pull/revert any changes made to files on the main branch.

2. What is the difference between Git and GitHub?
- Git is simply a set of commands that we can use in the terminal to connect a local computer
to GitHub repositories where we store, edit, and update files using Git commands. GitHub is a
cloud where repositories are stored. 

3. Why do we create a branch? 
- Creating a branch helps us compare the changes made to the files on the branch to the main branch,
and prevents any unnecessary direct changes that could cause files in the main branch to produce
erroneous results or errors.

4. What is the purpose of a Pull Request?
- Pull Requests are managed by the maintainer of the repository. The purpose of pull request is to
have the changes made to the files on our branch compared and reviewed by the maintainer of the
repository before merging the files back to the main branch.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
- To go back to the main branch, we can use: git checkout main
- An alternative way is to pass [-] to git checkout: git checkout -
	-This Alternative is a shortcut for returning to the previous branch we were on.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
- 'git fetch' downloads the data from remote repository to local repository which doesn't merge or
modify any work in progress. In order to merge the data in the local repository to the working
directory, I would have to do it manually by using the 'git merge' command.

- 'git pull' on the other hand, downloads the data from the remote repository to local repository and
then merges it to the working directory automatically without having to use 'git fetch' and 'git merge' commands.

7. What is a merge conflict?
- When another person deletes or makes changes to the same line of the same file, merge conflict happens, meaning merge branches have competing commits that would require us to choose which changes to incorporate in the final merge.

8. How do you resolve a merge conflict?
- When a merge conflict is caused by two people making different changes to the same line of the same
file, it can be resolved on GitHub using the conflict editor which is found under pull request tab
where we will see a button that says "Resolve conflicts." There, we can make the changes we want in the final merge. 

- Other types of merge conflicts can be resolved in a local clone of the repository and push the change to the branch on GitHub.

