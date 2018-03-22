Git is a version control system.
Git is free software ditributed under the GPL.

I have learned how to wirte a file in git bash, add and commit it.

touch file.txt
git add file.txt
git commit -m "add file.txt"


git status
use it to see current status

Learn how to change the version

git reset --hard HEAD^ or commit id
use this to change the head pointer

git log 
git log --pretty=oneline

git reflog

use these commend to see the changes


compare work dict and stage
git diff
compare stage and master
git diff --cached

cancel the modify in work dict
git checkout -- readme.txt

move the modify from stage to work dict
git reset HEAD readme.txt


create a new branch is quick.
