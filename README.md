# Intro-Github
Github Instructions and Help
How to Upload Files of Unity in Github - https://www.youtube.com/watch?v=YymhtHtHDb8



Github Commands 
Here are the commonly used Git commands with their meanings:

### **Configuration**
1. **`git config`**: Used to set Git configuration values, like your email, username, and line ending preferences.
   - Example: `git config --global user.name "Your Name"`

### **Creating Repositories**
2. **`git init`**: Initializes a new Git repository in the current directory.
   - Example: `git init`

3. **`git clone [url]`**: Clones a remote repository from a URL to your local machine.
   - Example: `git clone https://github.com/user/repo.git`

### **Working with Files**
4. **`git add [file]`**: Adds a file to the staging area (prepares it to be committed).
   - Example: `git add myfile.txt`
   
5. **`git add .`**: Adds all modified or new files in the current directory to the staging area.
   - Example: `git add .`

6. **`git rm [file]`**: Removes a file from the working directory and the staging area.
   - Example: `git rm myfile.txt`

7. **`git mv [oldfilename] [newfilename]`**: Renames or moves a file.
   - Example: `git mv old.txt new.txt`

### **Committing Changes**
8. **`git commit -m "[message]"`**: Records changes in the repository with a descriptive message.
   - Example: `git commit -m "Added new feature"`

9. **`git commit --amend`**: Edits the last commit or adds more changes to it.
   - Example: `git commit --amend -m "Updated commit message"`

### **Branching**
10. **`git branch`**: Lists all local branches.
    - Example: `git branch`

11. **`git branch [branch-name]`**: Creates a new branch.
    - Example: `git branch feature-branch`

12. **`git checkout [branch-name]`**: Switches to the specified branch.
    - Example: `git checkout feature-branch`

13. **`git checkout -b [branch-name]`**: Creates and switches to a new branch.
    - Example: `git checkout -b feature-branch`

14. **`git merge [branch-name]`**: Merges the specified branch into the current branch.
    - Example: `git merge feature-branch`

15. **`git branch -d [branch-name]`**: Deletes a local branch.
    - Example: `git branch -d feature-branch`

### **Remote Repositories**
16. **`git remote -v`**: Lists remote connections.
    - Example: `git remote -v`

17. **`git remote add [name] [url]`**: Adds a remote repository connection.
    - Example: `git remote add origin https://github.com/user/repo.git`

18. **`git push [remote] [branch]`**: Pushes local changes to the remote repository.
    - Example: `git push origin master`

19. **`git fetch`**: Fetches changes from the remote repository but does not merge them.
    - Example: `git fetch origin`

20. **`git pull`**: Fetches and merges changes from the remote repository into the current branch.
    - Example: `git pull origin master`

### **Stashing Changes**
21. **`git stash`**: Temporarily saves modified and staged changes.
    - Example: `git stash`

22. **`git stash pop`**: Applies the most recent stashed changes.
    - Example: `git stash pop`

### **Viewing History**
23. **`git log`**: Shows the commit history.
    - Example: `git log`

24. **`git log --oneline`**: Shows a condensed version of the commit history.
    - Example: `git log --oneline`

25. **`git status`**: Shows the status of files in the working directory and staging area.
    - Example: `git status`

26. **`git diff`**: Shows the differences between the working directory and the staging area.
    - Example: `git diff`

### **Undoing Changes**
27. **`git reset [file]`**: Unstages a file (but keeps changes in the working directory).
    - Example: `git reset myfile.txt`

28. **`git reset --hard [commit]`**: Resets the working directory and staging area to match a specific commit.
    - Example: `git reset --hard abc1234`

29. **`git revert [commit]`**: Reverts the changes made by a specific commit (creates a new commit).
    - Example: `git revert abc1234`

### **Tagging**
30. **`git tag [tag-name]`**: Creates a tag (like a version number) for a specific commit.
    - Example: `git tag v1.0`

### **Cleaning Up**
31. **`git clean -f`**: Removes untracked files from the working directory.
    - Example: `git clean -f`

These commands are the most common and will help you perform basic to advanced tasks in Git.
