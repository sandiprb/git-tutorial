# git-tutorial

Git
 - Code Repository
 - Collaboration for Developers
 - Version Control


 Day 1 - a1
 - This is my code

 Day 2 - a2
 - This code is written by me

 Day 3 - a3
 - This code is written by me and is uploaded on Githb

 Day 4 - a4
 - This code is written by me and is uploaded on Github


Commit
- a4
- a3
- a2
- a1


- Create remote repository
- Create Local repo
- Make new file in repo 
- see the status of file  
    ```
    git status
    ```
- Add file to staging
    ```
    git add . # add all file
    git add filename # add single file
    ```
- Commit file changes
    ```
    git commit -m "<message>"
    ```
- Check status once again
    ```
    git status
    ```
- Link Remote Repo with local repo
    ```
    git remote add <remote_name> <remote_url>
    ```
- Push to remote repository
    ```
    git push -u origin main
    ```
- Edit File 1 & Edit File 2
- Commit both the files and push to remote
