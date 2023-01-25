# how to use git =>

    ## install git
    ## git init on vs code
    ## git add <fileNames>
            ###  git add .
            ###  git add <fileName>
    ## git commit -m " comments"
        ### if we are committing first time then it will ask -> *** Please tell me who you are.
             Run
             git config --global user.email "you@example.com"
             git config --global user.name "Your Name"
             so log in to gitHub
    ## git config --global user.email "abc@gmail.com"
    ## git config --global user.name "abc def"
    ## git commit -m "first commit"
    ## git branch -M main
    ## git push -u origin main

 <!-- // remove any file -->

    ### git rm fileForDeletion.txt
    ### git commit -m "delete  file"
    ### git push -u origin main

 <!-- // remove any folder -->

    ### git rm -r  gitFile-Deletion
    ### git commit -m "deleting a folder"
    ### git push -u origin main

 <!-- delete previous user name and password -->

click on window button > credential manager > Windows credentials > Generic credentials
Next, remove or edit the Github keys.
you can add directly using cmd

<!-- Error: src refspec master does not match any – How to Fix in Git -->

https://www.freecodecamp.org/news/error-src-refspec-master-does-not-match-any-how-to-fix-in-git/

<!-- to check origin -->

git remote -v
