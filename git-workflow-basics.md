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
This converts your folder into a Git repository

#### Git Architecture (3 Areas)

_After git init, Git works in 3 areas:_
1. Working Directory (Workspace): Where you create/edit files
2. Staging Area: Where files are prepared before commit
3. Local Repository: Where final changes are stored permanently

   <img width="1024" height="600" alt="Image" src="https://github.com/user-attachments/assets/59942921-db68-41d7-9364-562ab20515d7" />
