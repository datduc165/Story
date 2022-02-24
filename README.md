Hi, 
this folder is to practice GIT and understand how this version control tool work using terminal in this case is git bash
- using git status will list all the untracked files(not yet in the staging area) in the working directory
- use "git add chapter1.txt" 
    - to add this file to the staging area
- use " git commit -m "YOUR MESSAGE" "to commit changes
- use " git log " to list the commits
- Working Directory - use git add -> staging area -use git commit -> Local Repository

- TO KNOW difference:
    - use " git diff "NAME of FILE" "
- TO go back the previous version (last check point) of the file once we know we are messed up
    - use " git checkout "NAME of FILE "

AFTER create git in your computer we want to push it remotely 
- login github 
- then create repository (remote/ online)
- copy the URL for the repo in this case is (https://github.com/datduc165/Story.git)
- go to the git bash and start add origin folder (working folder) / we are pushing our local working folder to the remote github
- git remote add origin https://github.com/datduc165/Story.git
- git push origin master (to push everything to the github remotely)
    - origin is the name 
    - master is the initial/root branch