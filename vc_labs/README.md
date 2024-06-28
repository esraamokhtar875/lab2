![random image](/home/esraa/pictures/download.jpeg)

<=====How to remove branches locally and remotly>

=to remove branch locally==

for our branches dev and test
======locally====
git branch -d dev
git branch -d test

====remotly====
git push origin --delete dev
git push origin --delete test



<========HOW to checkout another branch without commeting changes=======>

1- stash current changes:
git stash

2- checkout to another branch:
git checkout <branch-name>

3- Reapply the stashed changes if needed:
git stash pop

<====How to list tags===>
git tag


< ==== How to delete tag locally and remotly === >

===locally=
git tag -d v1.7

==remotly==
git push origin --delete v1.7
