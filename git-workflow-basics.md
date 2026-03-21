## _Git Workflow Basics (Working Area → Staging → Repository)_

### What is Git?
_Git is a **version control system (VCS)** used to track changes in source code._

#### It helps developers:
- Track history
- Collaborate with others
- Manage versions of code

####  Git vs GitHub

- **Git** → Software (installed locally)
- **GitHub** → Remote repository (cloud platform to store code)

####  Install Git (Linux - yum)
```bash
yum install -y git
```
#### Create Project & Initialize Git
```
mkdir project-name
cd project-name
git init
```
_This converts your folder into a Git repository_

#### Git Architecture (3 Areas)

_After git init, Git works in 3 areas:_
1. Working Directory (Workspace): Where you create/edit files
2. Staging Area: Where files are prepared before commit
3. Local Repository: Where final changes are stored permanently

   <img width="600" height="400" alt="Image" src="https://github.com/user-attachments/assets/59942921-db68-41d7-9364-562ab20515d7" />

#### Create Files
```
touch file1 file2 file3 file4 file5
```
_All files will be created in the Working Directory_

#### Add File to Staging Area
```
git add file1
```
_Moves file from Working Directory → Staging Area_

#### Add All Files to Staging
```
git add *
```
#### Remove File from Staging Area
```
git rm --cached file1
```
_Moves file from Staging → Working Directory_

#### Remove All Files from Staging
```
git rm --cached *
```
#### Commit Changes (Save to Repository)
- Commit Single File
```
git commit -m "your message" file1
```
- Commit All Files
```
git commit -m "your message"
```
_Moves files from Staging Area → Local Repository_
