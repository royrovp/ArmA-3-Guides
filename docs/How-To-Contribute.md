# How To Contribute
The minimum requirements are GIT and a GitHub account, but I strongly suggest you to install Notepad++ or Visual Studio Code which would make it easier to write the pages.  

# GIT
Git is a software which keeps track of all changes in a project. This lets us keep a history of how the project evolved and a lot of other things.  

## Instalation
Step 1: Go to the [official download page](https://git-scm.com/download)  
Step 2: Download the latest version (Standalone installer, 64 bit)  
Step 3: Run the installer and click next until you get to the `Adjusting your PATH enviroment` and select the third option  
Step 4: Click next until you get to `Choose the defult behavior of git pull` and select Rebase  
Step 5: Click next until you installed the software.

Now open a Command Prompt and type `git` to check if you've successfully installed it.

## Usage & Commands
Let's say we want to add a new feature.

Step 1: `git checkout main` - we switch to the main branch  
Step 2: `git pull` - need to make sure we have the latest changes  
Step 3: `git checkout -b branch_name` - create a new branch and name it however we want (a suggestive name is recommended though)  
Step 4: We write the modifications  
Step 5: `git add .` - adding all modified files to git so we can commit them.  
Step 6: `git commit -m "message which explains shortly what this commit does"` - commiting the changes (now these changes are in the git history)  
Step 7: `git push origin HEAD` - send the modifications to GitHub


# GITHUB
GitHub is a website which lets us share code and work together on one project.

Go to [GitHub](https://github.com/) and create a new account and then send your username to Roy so he can add you to the project.

## Usage
### Getting the source code
There are 2 ways we can download the source code: HTTPS and SSH. HTTPS is deprecated so we'll use SSH.

### Set up a SSH key
Step 1: Open a command prompt  
Step 2: Enter `ssh-keygen`  
Step 3: Spam the enter key until it finished generating your key  
Step 4: Go to C:\Users\YOUR_USERNAME\.ssh and open `id_rsa.pub` with notepad and copy all the contents  
Step 5: Go to github, click on your profile, go to Settings and click on the [SSH and GPG keys section](https://github.com/settings/keys)  
Step 6: Click `New SSH key`, paste the contents of your key, add a random title and click `Add SSH Key`

### Cloning the source code
Ok now that we've set everything up it's time to get the code.  
Choose a place where you want to download the code. I'll be using C:  
Open a command prompt and go to your folder (in my case I'll run `cd C:\`)  
Run `git clone git@github.com:royrovp/ArmA-3-Guides.git`  
Now you should have a new folder called Arma-3-Guides

### Creating a PR
After commiting a new change and pushing it to github you'll need to create a Pull Request (PR)  
Go to the [repo page](https://github.com/royrovp/ArmA-3-Guides) and click on Pull Requests  
Click on `New Pull Request`  
Click on `Compare: main` and select your branch  
Click on `Create pull request`  
Add a description if necessary and click on `Create pull request` again.
