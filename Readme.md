# How to use Git on Macbook 
This is to learn about the git
1.  for clone : git clone "SSH url"
2.  to see all files including the hidden files: ls -a
3.  check if files need to be commited or not :git status
4.  to commit :git add .
5.  then :git commit -m "(message for heading)" -m "(message for discription)"
6.  still its not live, for live : git push
7.  now the project is hosted to remote repo
8.  of creating a new repo on local computer then make a repo and then :git init
9.  git status
10. git add .
11. git commit -m ""
12. now if you add then you cant 
13. make a new repo on the git and then copy SSH 
14. :git remote add origin SSH-URL
15. to check :git remote -v
16. for setting upstream :git push --set-upstream origin main
17. now you can use just : git push

18. PROBLEM WHILE PUSHING TO REPO FROM LOCAL PC
19. First Do this ...

git fetch origin main
git merge  main

Then, do this ...

git fetch origin master:tmp

git rebase tmp

git push origin main

git branch -D tmp

Now everything works well.

BRACHING 
1.  when adding new features in the repo then use branching
2.  To the branches.. first type : git branch
3.  main shows that it is in the main branch (* shows that you are in that br)
4.  to check out :q
5.  to make branch (Name should be discriptive):git checkout -b NAME
6.  now you can check in which branch you are by just :git branch
7.  to switch between branches : git chekout NAME
8.  Checking it now in the feature 
