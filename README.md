# Github Terminal Command
> [!TIP]
> Helpful advice for doing things better or more easily.
## Optional
- cd C:\\...
> Switch to destination path. 
- git status
> Check tracked or untracked project files and the changes. 
<span title="hi is a hi">hi</span>

## Steps: 
1. Push the Project to Github
- git checkout -b "branch name"
> Create new branch and switch targeted path to created branch. 
- git add .   
> Select all files in the project folder.
- git commit -m "message"
> Add command on the changed files.
- git push origin "branch name"
> Push changes files to created branch in Github.

2) Create Pull Request in Github 
- Go to Github 
- Click "New Pull Request" 
- Click "Create Pull Request" 

3) Merge with Master Files 
- Click "Merge Pull Request"
> Merge master file with current changes. 
- Click "Confirm"                            
- Click "Delete Branch"
> To avoid duplicate branch names, can choose to save for backup purposes.

4) Pull the Merged Files from Github 
- Back to Software 
- git checkout master
> Switch back to main branch, default main branch usually named "Guideline".
- git pull                                 
> Pull the merged files from Github to local. 
- git branch -D "branch name"
> Delele created branch in local to avoid duplicate branch names, can choose to save for backup purposes. 

# Upload Large Files 
1) Install Upload Large File Github Command
2) Locate Large File
3) Upload to Github
