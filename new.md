How to Use Git & GitHub

1. Create New Repo in GitHub 

2. Clone Repo to Desktop
cd ~/Desktop/  
git clone (insert web link to GitHub folder)   
cd (insert repo name, i.e. name of folder) 
ls  
git remote -v   
If there is no origin listed, then $ git remote add origin (insert web link to repo folder)  

3. Edit Files in Cloned Repo
ls  
Open file in appropriate program from desktop to edit, edit, save file.  
git status  

4. Add a New File in Cloned Repo
touch (name of file.ext)  
ls  
Open file in appropriate program to edit, edit, save file.  
git status  

5. Stage Files for Commit
git add (insert specific file name)  
OR
git add .  
git status  

6. Commit Changes 
git commit -m "insert description of commit"  
git status  
git log  

7. Push Changes to GitHub Repo
git push origin master    