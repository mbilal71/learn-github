# Git
Learn Git from Scratch with Muhammad Bilal Siddique
# Install # Installations and project starter kits

## Installations:

1.  Install Git from (https://git-scm.com/) Latest source Release 2.43.0 Release Notes (2023-11-20).

# Installlation process - Step by step.
![git1](https://github.com/mbilal71/learn-github/assets/107579362/5ac21ab4-8b7f-4f7c-891c-df35a7916e94)



![git2](https://github.com/mbilal71/learn-github/assets/107579362/ad16c301-170d-4f2d-a7bb-36b62c79b511)



![git3](https://github.com/mbilal71/learn-github/assets/107579362/99296000-b6d5-4125-aede-df3352ac0d91)



![git4](https://github.com/mbilal71/learn-github/assets/107579362/8a0b4182-e64a-4a4a-b023-876ba6c487dd)



![git5](https://github.com/mbilal71/learn-github/assets/107579362/1034efe9-ffb1-4733-b053-999d4dfa1a79)




![git6](https://github.com/mbilal71/learn-github/assets/107579362/dbce0203-b7f8-462a-8c7f-0c77b9e1c591)



2.  Launch Git Bash




![git7](https://github.com/mbilal71/learn-github/assets/107579362/7e00a704-748a-4d15-bfab-92a46d5ea7d1)




 After launching Git Bash proceed for the following commands at Git Bash prompt:-
 
 

        `$ git -v`   # It will show the version of Git.

        Get your user name and email from [Github](https://github.com/)

        `$ git config --global user.name "Your user name"`

        `$ git config --global user.email "Your email"`

![GitBash](https://github.com/mbilal71/learn-github/assets/107579362/e8ec0680-9fec-4ffc-9b65-6e15b1ec7694)


3.  Now open your vscode and go to terminal.

4.  For every new project.
            
         `git init`
                
         `git remote add origin "https://github.com/mbilal71/learn-github.git"`
            
         `npm i -g typescript`
5.  For every new change repeate these commands:-

         `git add -A`
    
         `git commit -m "Name your Changes"`

         `git push origin master`

    

To change the branch of an existing repository on GitHub, you can either create a new branch, switch to an existing branch, or rename the current branch. Here are the steps for each scenario:

### 1. Switch to an Existing Branch

If you want to switch to an existing branch:

1. **Fetch the latest changes from the remote repository:**
    ```sh
    git fetch
    ```

2. **List all branches (optional):**
    ```sh
    git branch -a
    ```

3. **Switch to the desired branch:**
    ```sh
    git checkout branch-name
    ```

4. **Pull the latest changes for that branch:**
    ```sh
    git pull origin branch-name
    ```

### 2. Create a New Branch

If you want to create a new branch:

1. **Create and switch to a new branch:**
    ```sh
    git checkout -b new-branch-name
    ```

2. **Push the new branch to the remote repository:**
    ```sh
    git push origin new-branch-name
    ```

3. **Set the upstream branch for the new branch:**
    ```sh
    git push --set-upstream origin new-branch-name
    ```

### 3. Rename the Current Branch

If you want to rename the current branch:

1. **Rename the current branch:**
    ```sh
    git branch -m new-branch-name
    ```

2. **Delete the old branch on the remote (if needed):**
    ```sh
    git push origin --delete old-branch-name
    ```

3. **Push the new branch to the remote:**
    ```sh
    git push origin new-branch-name
    ```

4. **Set the upstream branch for the renamed branch:**
    ```sh
    git push --set-upstream origin new-branch-name
    ```

### Example Steps in Detail:

1. **Switch to an Existing Branch:**
    ```sh
    git fetch
    git branch -a
    git checkout existing-branch
    git pull origin existing-branch
    ```

2. **Create a New Branch:**
    ```sh
    git checkout -b new-feature-branch
    git push origin new-feature-branch
    git push --set-upstream origin new-feature-branch
    ```

3. **Rename the Current Branch:**
    ```sh
    git branch -m new-branch-name
    git push origin --delete old-branch-name
    git push origin new-branch-name
    git push --set-upstream origin new-branch-name
    ```

### Notes:

- Make sure you have committed any changes before switching branches to avoid losing any work.
- Renaming the default branch (usually `main` or `master`) on GitHub requires updating the default branch setting in the repository settings on GitHub as well.

### Best of Luck!

