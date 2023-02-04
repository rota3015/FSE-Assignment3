# FSE-Assignment3


git commit --amend -m "commit 0" //update the name of existing commit to commit 0

git checkout -b bug-fix		//creating new branch bug-fix
git commit -m "commit 3 refers to commit 0"" // creating new commit on new branch

Git add .
git commit -m "commit 4 refers to commit 3" // creating new commit commit 4

/////// <<<< HEAD conflicts that we resolved
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
//// ==== resolved conflicts
git checkout -b test_branch //created a test_branch from commit 2

git checkout bug-fix //switched to bug-fix branch to create new bug-fix-experimental branch

Git checkout -b bug-fix-experimental //created and switched to bug-fix experimental branch

Git add .
Git commit git commit -m "commit 7 referencing commit 4"

Git add .
Git commit git commit -m "commit 8 referencing commit 7"

Git add .
Git commit git commit -m "commit 9 referencing commit 8"
//// >>> bug-fix-experimental resolved conflicts

Git checkout bug-fix // checking out to bug-fix branch
Git merge bug-fix-experimental // merging the bug-fix-experimental into bug-fix and resolving conflicts
Git add .
Git commit -m "merge commit 11 referencing to commit 6 and commit 9"


Git add .
Git commit -m "commit 12 referencing to commit 11"