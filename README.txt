Collaborate on Github for a Contributor

---Initial Setup---
 1.) Fork the repo from Github (into desired directory)
 2.) git clone <forkedRepoName>
 3.) git init
4a.) git remote add upstream <forkedRepoName>
 
 ---Common Procedure for Commit and Update--- 
 5.) git checkout -b <branchName>
 6.) Do Code
 7.) git add -A (to add all)
 8.) git commit -m "initial commit"
 9.) git push origin <branchName>
10.) Create Pull Request on GitHub (on contributors github file) 

---After Pull Request Approved and Merged---
11.) git checkout master
12.) git pull origin <branchName>
13.) Repeat steps 6-13

 ---To Get Contributor Up-to-Date with Original Repo---
4b.) git pull upstream master (make sure you're on master if wanted)