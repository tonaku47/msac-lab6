# Exercise 8 - Viewing changes before committing

1. Ensure your working directory is clean

2. Add text to any one of your files

3. Delete different text from another of your files

4. Look at `git status`

5. View all the changes you've made

        git diff

6. Does the following command return anything?

        git diff --staged

7. Add one of your changed files to the index

        git commit add <changed file>

8. What do these commands show?

        git diff this is not show
        git diff --staged yes it shows


9. Add the other changed file to the index

        git commit add <other changed file>

10. What do these commands show?

        git diff
        git diff --staged

11. Commit the changes

12. Check that your working directory is clean

13. Create a new file named `clothing.txt`

14. Does the new untracked file show up in git diff?

        git diff

15. Add and commit the new file
