# demo 

some descraption
## git stander used
git init
git remote add origin https://github.com/alaa19090/git-test.git
git add .
git remote -v
git status
git commit -m "creat readme file "
git commit -am "tayping some text"
git push -u origin master
  
## git branch


git branch

### for new branch
#### when we on anuther branch we have a cope is diffrent on the master cope   
git checkout -b new-brsnch or git branch new-branch -> git checkout new-branch 

I will do some chaings like I will add some file on new-branch

git add index.html
git commit -m "creat the index file"
git checkout -b master 

and change will be effict just on the new-branch

git diff new-brsnch
//to see the files differences between the branches