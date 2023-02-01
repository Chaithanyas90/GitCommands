# GitCommands

**Different kinds of Version controls:**
  1. Local VCS
  2. Centralized VCS
  3. Distributed VCS

**Advantages of using VCS:**
1. Collaboration: Shared workspace and real time updates
2. Manage Versions:
3. Rollbacks:
4. Reduce Downtime:
5. Analyse Projec: 


**Tracking files in local:**
  1. git init

**...To be added**

**Adding remote repo to your local**
  1. **Git init**
  2. **git remote add origin** https://github.com/Chaithanyas90/GitCommands.git
  3. **git pull** (Take a pull before pushing any code)
  4. **git remote -v** (Lists the origin of the origin fetch and origin push)

**Rename the origin of repo (This rename is only for the local)**
  1. **git remote rename origin new_name**
  2. **git remote rename new_name any_name**

**Remove remote repo**
  1. **git remove remote origin**
  2. **git remote rm origin**

**Delete old Branch**
  1. **git push origin --delete old_Branch** - Delete old branch present in remote
  2. **git branch -d old_branch** - Delete Branch from remote machine
  3. **git push -delete origin branch_name** - Delete remote branch
  4. **git push -f origin branch_name**

**Rename Branch**
  1. **git branch -m new_name_for_the_branch** - Current branch name changes to the name mentioned
  2. **git branch -m old_branch new_name_For_the_branch** - changes the name of old-name to the new name specified
  3. **git git push origin :old_name new_name** - Reflect the changes in the remote machine

**File Locations pre and post commit (File can contain in three locations but with different code)**
  1. Committed inside the repo
  2. Staged in the index
  3. Workspace

**Find the differences**
  1. **git diff branch_name** -Compares with the indexed version
  2. **git diff --cached text.txt** - Compare with the remote branch
  3. **git diff <branch_1> <Branch_2>** COmpares the code between two different branches
  4. **git diff --staged text.txt** - Compare with the staged 
  5. **git diff commit_id text.txt** compare the current file status with commit id

**Compare Local git branch with remote**
  1. **git fetch <remote_branch_path>** - Update remote tracking branchs
  2. **git diff <master_branch_path> <remote_branch_path>**
  3. **git branch -a** - Lists all the branches

**Fork a Repo from GitHub (Used for bugfixes)**
  1. On Github, navigate to the repository which you want to fork
  2. In top-right corner of the page, click fork.
  3. After fork, to work on local repo either clone or download it.

**Pull Request**
  1. git clone httplink
  2. git checkout -b "LocalBranch"
  3. git add .
  4. git commit -m "COmmit message"
  5. git push --set-upstream origin master
  6. a new b
