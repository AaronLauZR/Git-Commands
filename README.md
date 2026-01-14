# Push/Pull Terminal Command
> [!TIP]
> <span title="Check tracked or untracked project files and the changes.">git status</span> 

## Steps
1. Push the Project to Github
    - <span title="Locate to destination file path.">cd C:\\...\\...\\...</span> 
    - <span title="Create new branch and switch targeted path to created branch.">git checkout -b "branch name"</span>
    - <span title="Select all files in the project folder.">git add . </span>
    - <span title="Add command on the changed files.">git commit -m "message"</span>  
    - <span title="Push changes files to created branch in Github.">git push origin "branch name"</span>

2) Create Pull Request in Github 
    - Go to Github 
    - Click "New Pull Request" 
    - Click "Create Pull Request" 

3) Merge with Master Files
    - <span title="Merge master file with current changes.">Click "Merge Pull Request"</span>
    - Click "Confirm"                            
    - <span title="Optional: Delete(github side) to avoid duplicate branch name, or can choose to save for backup purpose.">Click "Delete Branch"</span>

4) Pull the Merged Files from Github 
    - Back to Software 
    - <span title="Switch back to main branch, default main branch usually named 'Guideline'.">git checkout master</span>
    - <span title="Pull the merged files from Github to local.">git pull </span>
    - <span title="Optional: Delete(client side) to avoid duplicate branch name, or can choose to save for backup purpose.">git branch -D "branch name" </span>                            
# Upload Large Files 
> [!NOTE]
>  Complete Below Steps in Command Prompt

## Steps 
1) Install Upload Large File Github Command
    - git lfs install

2) Locate Large File
    - <span title="Locate local github repository folder.">cd C:\\Users\\...</span>
    - <span title="Track the type of large file, for example:'.bak', '.h5'. * is for any filename.">git lfs track '*.bak'</span>
    - git lfs push --all origin main</span>          
    - <span title="Select all files in the project folder.">git add .</span>

3) Upload to Github
    - <span title="Add command on the changed files.">git commit -m "message"</span>
    - <span title="Push changes files to Github.">git push -u origin master </span>

# Edit Commit Date/Time
> [!NOTE]
>  Complete Below Steps in Command Prompt

## Steps
1) Locate to Local Repository Folder
   - cd ...
   - <span title="Switch to target branch if got several branch existed.">git branch</span>

2) Edit First Commit Date & Time
   - git commit --amend --no-edit --date="YYYY-MM-DD HH:MM:SS"
  
3) Edit Latest Commit Date & Time
   - set GIT_AUTHOR_DATE=YYYY-MM-DD HH:MM:SS
   - set GIT_COMMITTER_DATE=YYYY-MM-DD HH:MM:SS
   - git commit --amend --no-edit
