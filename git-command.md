to check the status of git (vcs)
```
git status
```
2. to update the remote repo url
```
get remote set url origin [your repo url]
```
to verify/DISPLAY added remote url 
```
git remote -v
```
9. to config the user.name andd user.email;
```
Project Based Config:
git config user.name[ur_github_user.name]
git config user.email[ur_github_user.email]

GLOBAL Config:
git config --global user.name[ur_github_user.name]
git config --globa user.emai[ur_github_user.email]

to verify / display config(note: enter to view more config and q to exit the open editor):
```
git config --list
```
# after changing on project 
1. git add .
2. git commit -m"[ur_commit_message]"
3. git push 

# using personal acess token (PAT)on https url:
git remote and origin http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
