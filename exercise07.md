# Exercise 7 - More than one changed file

1. Ensure you have a clean working directory

        git status

2. Edit one of your `fruits.txt`, add a few items

        blueberry
        strawberry
        etc.

3. Edit `appliances.txt` and add a few items

        dishwasher
        dryer
        etc.

4. Look at git status, paste the output here

        git status

5. Can you commit both of the changed files in a single commit?

6. After you do so, check that you have a clean working directory by running `git status`, and pasting the output here

anthonypark@anthonys-mbp my_repository % git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   equipment/appliances.txt
	modified:   fruits.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store

7. Create a new file `equipment/furniture.txt`. Add content to both `vegetables.txt` and `furniture.txt`

8. How can you commit just one of the changed files?

9. Check your `git status`

10. What does red text mean in the output of `git status`?

red text means it does not process and also untrackable folders or file. It may consider for a deletion, but it still does not into the commit until the user commits or not. 

11. What does green text mean in the output of `git status`?

green text means it gives us an indicator in order to add if necessary.

12. How can you make a single file show in both red and green in the output of `git status`?

Git status then untrackable folder then git add "commit" again "git status then git commit -m "added more fruits.txt appliance.txt" then green commit. 