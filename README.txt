Steps on Github for a Originator

---Initial Setup---
 1.) Create repo on Github
 2.) mkdir <directoryName>
 3.) cd into directory
 4.) git init
 5.) Follow Steps on Github
 
 ---Common Procedure for Commit and Update--- 
 6.) git checkout -b <branchName>
 7.) Do Code
 8.) git add -A (to add all)
 9.) git commit -m "initial commit"
10.) git push origin <branchName>
11.) Create Pull Request on GitHub (on originators github file)

---After Pull Request Commment/Approved and Merged---
12.) git checkout master
13.) git pull origin master (to get master up to date from Github)
14.) Repeat steps 5-12

Collaborate on Github for a Contributor

---Initial Setup---
 1.) Fork the repo from Github (into desired directory)
 2.) git init 
 3.) git clone <yourForkedRepoName>
 4.) change directory to created folder
 5.) git remote -v (to see what upstream/origin are set)
6a.) (If missing origin) git remote add origin <yourForkedRepoName>
6b.) (If missing upstream) git remote add upstream <originalRepoName>
 
 ---Common Procedure for Commit and Update--- 
 7.) git checkout -b <branchName>
 8.) Do Code
 9.) git add -A (to add all)
10.) git commit -m "initial commit"
11.) git push origin <branchName>
12.) Create Pull Request on GitHub (on contributors github file) 

---After Pull Request Approved and Merged---
13.) git checkout master
14.) git pull origin <branchName>
15.) Repeat steps 6-12

 ---To Get Contributor Up-to-Date with Original Repo---
5c.) git pull upstream master (make sure you're on master if wanted)






To-Do:

1.) Non-orginator merge/approve pull requests
2.) Practice merge conflicts
3.) Make another repo and adjust steps where needed
4.) Charlie: make terminal prettier
