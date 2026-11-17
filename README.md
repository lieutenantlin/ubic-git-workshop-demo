# UBIC Git Workshop Demo
Repository to practice Git skills in UCSD's UBIC Week 8 Workshop

## Push and resolve a merge conflict

After committing, your changes only live on your computer. To send them to github, we have to push our code.

### Let's practice resolving merge conflicts!

Merge conflicts happen when two branches change the same line of code.

1. Make a practice branch:

git checkout -b yourname/conflict-practice

2. Edit a line in README.md: For example, you can change the title. Once you're done, state and commit your changes.

3. Switch back to the main branch:

git checkout main

4. Edit the same line in README.md, and stage and commit your changes.

5. Merge the practice branch into main:

git merge yourname/conflict-practice

### Now let's fix the merge conflict

Open README.md. You will see the conflict. The text above the ===== line is your change, and the text below is the original. Decide what the changed line should be, then delete the marker lines (these lines: <<<<<< ====== >>>>>>).

Lastly, run these commands:

git add README.md
git commit -m "Resolve merge conflict"
git push origin main

When you open README.md, there should be no more markers left.
