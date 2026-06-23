# learningGithub
learning git and github
<br>
Setting up Git
<br>
Download: Windows(Git Bash)
<br>
Terminal: git --version
<br>
Configuring Git
<br>
git config --global user.name "username"<br>
git config --global user.email "emailId"<br>
git --config --list<br>


Copying a repo into local system<br>
git clone (link)

<br>
To check the status of git
<br>
git status
<br>
untracked: new files arent tracked by the git yet<br>
modified: changed<br>
staged: file is ready to be commited<br>
unmodiified: unchanged<br>

Add and Commit
Add:<br> 
git add (file name) : adds new or changed file<br>
git add . : adds all files<br>

Commit:<br>
git commit -m "message" : commits with message(record)<br>

Push Command: Upload local repo content to remote repo

Init Command: used to create a new git repo

git init

git remote add origin (link)

git remote -v [to verify branch]

git branch [To check branch, usually master change it to main ]

git branch -M main [rename branch]

git push origin main


Github Branches

git branch [To check branch, usually master change it to main ]

git branch -M main [rename branch]

git checkout (branch name) [to navigate]

git branch -d (branch name) [To delete branch]

git push origin (branch name)


Merging Code

Way 1:
git diff (branch name)
git merge (branch name)

Way 2: Create a pull request (Compare and merge through GitHub)

Pull Command: Used to fetch content from remote repo
git pull origin main

Undoing Changes

Case 1: Staged only chnage
git add. 
git status
git reset (file name)
git reset[For all files]

Case 2: Committed changes (for one commit)
git reset HEAD~1

Case 3: Multiple Committed changes
git reset (commit hash )
git reset --hard (commit hash)

git log [to know all history and hash]