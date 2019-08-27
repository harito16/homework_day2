1. What command do you use to setup a git repository inside of your folder? git init

2. What command do you use to ask git to start tracking a file?
git add . 

3. What command do you use to ask git to move your file from the staging area to the repository?
git commit -m ""

4. What command do you use to get updates from the class repository?
git pull upstream master

5. What command do you use to push your work to your fork of the class repository?
git push master origin


Answer more questions!

1. What command do you use to unstage a file? 
git reset HEAD <file>

2. What command do you use to change your files back to how they were after a commit?
git checkout -- <file>

3. Why is it important to use -- when changing files back to a previous state?
With git checkout -- <file> you can be specific as to which file you want to revert. 

4. Why might you want to reset your files back to a previous commit?
If you didn't like the changes that you made and they're already commited. It's something like wanting to change your fiance once you are engaged. 