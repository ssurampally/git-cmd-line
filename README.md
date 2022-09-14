# git-cmd-line

Working with Git operations using Git - BASH terminal in VS code editor.

Download and Install Git:
https://git-scm.com/download/win

----------------------
Access the Git Repo in VS code Editor.

Open the bash Terminal in VS

Navigate to the folder to which repo should go.

$ git clone <https repo url>.

// repo is cloned to this folder.

Open the local repo folder in VS Code Editor., then you can see currently checkout branch.

once the file is modified or a new file created. Save it in the Workspace. it turns to M version. 

Stage the changes by running below command
$ git add .

then commit the changes 
$ git commit -m "information text"

then Push the changes to remote repo.
$ git push origin main

you can also stage, Commit and Push from VS code Git graphically.
 just make sure your giving user email and name in global config parameter.

$ git config --global user.email "sreekanth.surampally@gmail.com"
$ git config --global user.name "ssurampally"
--------------------------------------------




