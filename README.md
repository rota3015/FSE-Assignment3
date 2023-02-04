# FSE-Assignment3


git commit --amend -m "commit 0" //update the name of existing commit to commit 0

git checkout -b bug-fix		//creating new branch bug-fix
git commit -m "commit 3 refers to commit 0"" // creating new commit on new branch

Git add .
git commit -m "commit 4 refers to commit 3" // creating new commit commit 4

Git checkout main //checking out to main first branch
Git add .
Git commit -m "commit 1 referring to commit 0"

Git add .
Git commit -m "commit 2 referring to commit 1"

git checkout bug-fix //moved to bug-fix branch bug-fix experimental
Git merge test_branch //merged the test_branch into bug-fix branch
Git branch -D test_branch //deleted test_branch

Git add .
git commit -m "commit 6 referencing commit 5" 
