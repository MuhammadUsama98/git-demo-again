# git-demo-again
- 1 create a repo on github
- 2 created a same name folder in local in your pc
- 3 create any file in that folder for versioning
   -  echo "# git-demo-again" >> README.md
- 4 initialize git in your local folder
   - e.g : 'git init'
- 5 to check the status (untracked - 'red'/track file - 'green')
   - eg: "git status"
- 6 to move file from untrack to track file
   - eg: "git add ." (add all files into tracking)
   - eg: "git add file name" (add only specific file)
   - eg: "git add *.csv" (add only specific file)
   -  let suppose you want to move file from tracking to untrack
   -  eg: "git rm --cached file name"
- 7 to make file ready to push we do commit
   - eg: git commit -m "any meaningful message"
- 8 to rename the branch from master to main
   - eg: git branch -M main
- 9 to set the origin for your local repo for github repo
   - eg: git remote add origin https://github.com/MuhammadUsama98/git-demo-again.git
- 10 to push file from local to github repo
  - eg: "git push -u origin main"

# second time 

- git add.
- git commit -m "second time"
- git push
- 