### Git
 
#### Version Control System (VCS)
 
Git : distributed version control system
 
Purpose:
- track file changes
- manage versions
- support collaboration
 
#### Repository
 
Repository : project storage managed by Git
 
git init : initialize repository
 
ex)
git init
 
#### Git Workflow
 
Modified : file changed
 
Staged : ready to commit
 
Committed : saved snapshot
 
Flow:
 
Modified
→ Staged
→ Committed
 
#### Check Status
 
git status : show repository status
 
ex)
git status
 
#### Stage Files
 
git add file_name : stage one file
 
git add . : stage all files
 
ex)
git add report.txt
git add .
 
#### Commit
 
git commit -m "message" : save snapshot
 
ex)
git commit -m "first commit"
 
#### Remove From Staging
 
git rm --cached file_name : unstage file / stop tracking
 
ex)
git rm --cached report.txt
 
#### Configuration
 
System : all users
 
Global : current user
 
Local : current repository
 
Priority:
 
local > global > system
 
#### Ignore Files
 
.gitignore : ignore files from tracking
 
ex)
 
*.log
*.tmp
node_modules/
 
#### Typical Workflow
 
git init
 
git status
 
git add .
 
git commit -m "commit message"
 
#### Tip
 
git status
 
- check before commit
- check staged files
- check modified files
 
#### Tip
 
Commit Message
 
Good:
- fix login bug
- update README
- add search feature
 
Bad:
- update
- change
- test
 
#### Be Careful
 
git add .
 
- stages every changed file
- check with git status before commit
 
#### Be Careful
 
git rm --cached file_name
 
- removes tracking only
- file remains on disk
 
#### Important Keywords
 
VCS
 
DVCS
 
Repository
 
Modified
 
Staged
 
Committed
 
Commit
 
.gitignore
 
git init
 
git add
 
git status
 
git commit
 
git rm --cached
