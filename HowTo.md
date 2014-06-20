How to Use Git & GitHub
========================

1. Create New Repo in GitHub 
------------------------------
* *please include a readme.md file (check this box first before doing the rest)*

2. Clone Repo to Desktop
-------------------------
* $ cd ~/Desktop/  -> changes working directory to the desktop
* $ git clone (insert web link to GitHub folder) -> clones repo in GitHub to desktop  
*note: you may have to type in username and password here*    
* $ cd (insert repo name, i.e. name of folder) -> changes working directory to the cloned repo  
* $ ls -> lists the files in the repo  
* $ git remote -v -> references to repos not on my computer   
* *There should be an origin remote; it's created automatically with the cloning process. If no origin is available, then complete the following step.*  
* If there is no origin listed, then $ git remote add origin (insert web link to repo folder)

3. Edit Files in Cloned Repo
------------------------------
* $ ls  
* Open file in appropriate program from desktop to edit, edit, save file.  
* $ git status  

4. Add a New File in Cloned Repo
---------------------------------
* $ touch (name of file.ext)  
* $ ls  
* Open file in appropriate program to edit, edit, save file.  
* $ git status  

5. Stage Files for Commit
--------------------------
* $ git add (insert specific file name)  
* $ git add .  -> adds all new files in working directory 
* $ git status

6. Commit Changes 
------------------
* $ git commit -m "insert description of commit"  
* $ git status  -> confirm there is nothing else to commit  
* $ git log  -> confirm the commit is present
* *This affects local repo only; you still need to push changes the GitHub repo.*  

7. Push Changes to GitHub Repo
-------------------------------
* $ git push origin master  -> push master branch to origin remote (GitHub Repo)   
* *note: you may need to add username and password*  
* Refresh GitHub to confirm new files were pushed  

Kevin Markham is rockstar; there are no words to express my gratitude for the videos he has created.  The content above is a summary of some of his youtube videos that I found particularly useful.  This was created for easy reference in the event I don't have access to youtube.com.  Please see his amazing videos [here.](https://www.youtube.com/user/dataschool)  Thank you!