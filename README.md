Learning Git Commands

//go to the directory

git init
git add .  |  git add name_of_file.extension
git status
git commit -m "commit_message"

git restore --staged file_name.txt  (removes the edited history)
git log (all logs of edits)

git reset commit_id  (restore the project what it was just after that commit)

git stash  (restore the code to what it was in the last commit and backstages current code)

git stash pop  (bring backstaged back to front stage)

git stash clear  (remove the backstage the code)

git remote add origin https://github.com/sainikeshav/<repo_name>.git
git remote -v (gives additional info)

git remote rm origin

git branch  (print name of all branches)
git branch branch_name (create new branch)
git checkout branch_name (move head to branch_name)

git merge branch_name  (branch will be merged in main branch)
git push origin branch_name

upstream is the url from where the code was forked


//pull request
