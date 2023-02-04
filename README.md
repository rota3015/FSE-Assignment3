# FSE-Assignment3

git commit --amend -m "commit 0" //update the name of existing commit to commit 0

git checkout -b bug-fix		//creating new branch bug-fix
git commit -m "commit 3 refers to commit 0"" // creating new commit on new branch

Git add .
git commit -m "commit 4 refers to commit 3" // creating new commit commit 4

git checkout -b test_branch //created a test_branch from commit 2

git checkout bug-fix //switched to bug-fix branch to create new bug-fix-experimental branch

Git checkout -b bug-fix-experimental //created and switched to bug-fix experimental branch

Git add .
Git commit git commit -m "commit 7 referencing commit 4"

Git add .
Git commit git commit -m "commit 8 referencing commit 7"