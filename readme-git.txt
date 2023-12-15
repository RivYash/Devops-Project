#git-init command (for creating new repositories).

git init
git remote add origin <link>
git remote -v (to verify remote)
git branch (to check branch)
git branch -m (to rename branch)
git push origin main


git checkout -b <--branch name-->  (creating new branch)
git checkout <--branch name--> (switching branch)

git branch -d <-branch name-> (deleting branch)

# merging code

git diff <-branch name-> (to compare commits ,branches, files and more)
git merge <-branch name->


git pull origin main (to update the existing branch/repository)

git log (history)

# undoing changes
case 1: staged changes
    git reset (for many files)
    git reset <-file name-> (reset all specific file changes)

case 2: commited changes(for one commit)
    git reset HEAD~1 (changes commit)

case 3: commited changes (for many commits)
    git reset <-commit hash->\
    git reset --hard <-commit hash->