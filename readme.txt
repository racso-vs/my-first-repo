Part 3: Your first commit
1.What command shows you the current state of your repository?
-> git status 

2.What command stages readme.txt for commit?
-> git add readme.txt

3.What command commits with the message "Add readme file"?
-> git commit -m "add readme file"

4.What command shows your commit history?
-> git log

Part 4: Make Changes
1.Edit readme.txt and add a new line of text
There it is the new line of text

2.What does git status show now? Describe in your own words.
->It first shoes where am I (on which branch), then that there are modifications that wont be validated, to do so I need to do "git add <file>", finally that there are no modifications done or added for the moment, I need to do git add and git commit -a.

3.Stage and commit your changes with an appropriate message.

4.How many commits do you have now?
-> Since I am writing my answer to the question inside this file i have 3 commits, first the add of the file then 2 update of the answers to the questions.

Part 5: Exploration
Try these commands and describe what they do:

git diff
git log --oneline

->git diff, it shoes what i did on the file which is not (added, commited and pushed) to the git.
->git log --online it displays the 3 messages of the 3 commits 

Part 6: Working with Branches
1.What command lists all branches in your repository?
-> git branch --all

2.What command creates a new branch called feature-script?
3.What command switches to the feature-script branch?
->we can use to just create a branch : git branch "name-of-branch"
->to swith then : git switch "name-of-branch"

4.What single command creates and switches to a new branch called dev?
->git switch -c dev 
->git checkout -b dev

5.Switch back to the feature-script branch.
to do so i did : git switch feature-script

6.Verify you are on the correct branch
to do so i did : git branch
Since the only branch which was displayed in green was "feature-scripted", i knew i was on the correct branch.

Part 8: Merge Branches
3.What command merges feature-script into main? 
->git merge feature-script (when we are on the main branch)

4.List the files again. What changed?
->we see the file install.sh being on the main branch

5.Check your commit history. What do you observe?
->we observe the merge with "Head -> main"

6.What command deletes the feature-script branch after merging?
->git branch -d "feature-script"

