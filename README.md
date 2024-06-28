# new repository

<!-- here we created this repo using git init command on our local system-->

<!-- Pushing local repository from machine to github online -->
for this firstly create new repo on github get its link type the below command
git remote add origin https://github.com/puneetSawhaney/TestRepo.git


git remote -v  ::: command to verify remote above command 

git branch     :::  to check the branch


git branch -M main    :::   to rename branch

git push origin main

Another command

git push -u origin main ::: this command sets the origin to main and from next time we can use only git push

the push will be applicable to main branch and same repo origin used

and if only one file is modified 
then add and commit can be done in one command :::: command for that =>> git commit -am "Commit Message"