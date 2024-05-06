--------------Important Git Commnd for Version Control--------------

1:- git log   ---> this Commnd used to ckeck our all saved check points or commit done 
                   with deatiled information

2:- git log --oneline   ---> this Commnd used to ckeck our all saved check points or commit done without deatiled information 

Tips:- if you want to untacked your any file in our folder so make a file with name of
      .gitignore and open it and write the name of file with extention do you want to
       untacked

 3:- git status -s   ---> this command used to check the status of file
      answer just like 1:  A - added file in git 
                       2:  M - modified file in git 
                       3:  U - untracked file in git
                       4:  AM- modified file without added

4:-  git revert commit id name  ---> this commond used to go you previous check points    or commit example..   git revert e3s6d24   
here e3s6d24 is only example id name you can see  your commit id just type this commond 
git log --oneline

5:- git reset --hard HEAD~1  --> this commond used to delete our nearest previous commit 

6:- rm -rf .git --->  this commond used uninitialize git from your folder so open your folder with gitbase and type this coomand 
     rm -rf .git 

