# Git and Github

## Connection between Github and Local host

![Screenshot 2022-08-01 at 11 55 52](https://user-images.githubusercontent.com/102330725/182133424-7df876f0-554a-43bc-948d-86e79d38226a.png)

## Steps to create a git repository

**Step 1:** Click on the profile icon at the top right corner and select "Your repositories"

![Screenshot 2022-08-01 at 11 57 26](https://user-images.githubusercontent.com/102330725/182133693-0493eec8-b552-4d88-a978-19b0fe9c2ce7.png)

**Step 2:** Click on "New" button

![Screenshot 2022-08-01 at 12 01 26](https://user-images.githubusercontent.com/102330725/182134337-beb47d7c-f0c4-4d1a-b721-577c1c7da773.png)

**Step 3:** Provide a name for the repository, set it to public and click on "Create repository"
![Screenshot 2022-08-01 at 12 02 16](https://user-images.githubusercontent.com/102330725/182134462-60d5f0c4-7008-4ffd-a82d-c6ec24d51479.png)

**Step 4:** Once done, a quick setup page opens up, we need to follow the commands of quick set-up on the terminal, but before that, follow the steps below:

*i: Open terminal*

*ii: Go out of all the folder by `cd `*

*iii: Make a new directory by using the command: `mkdir`*

*iv: Create readme file: `nano README.md`*

*v: To view contents of the file: `cat README.md`*

*Note : Make sure that their is no master or main beside the file name at this stage, if there is run command: `-rm -rf filename`*

*Other commands on command line: *

*`ls` can be helpful in listing all files in the current directory.*

*`ls -a` lists all hidden files in the current directory.*

*`pwd` shows the current filepath.*

**STEP 5:** Once done, run the commands on the quick set-up page one by one.

![Screenshot 2022-08-01 at 12 04 31](https://user-images.githubusercontent.com/102330725/182136243-deb07bc0-8aef-4884-bcbc-6071ac564498.png)

```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin *HTTPS/SSH LINK HERE*
git push -u origin main
```

## Importance of the commands mentioned above

**init**: Creates an empty Git repository or reinitialize an existing one

**add**: Add file contents to the index

**commit:** Record changes to the repository

**push:** Update remote refs along with associated objects


 ## Commands used when working on existing repositories 
 
 **pull:** Fetch from and integrate with another repository or a local branch
 
 **clone:** Clone a repository into a new directory
 
 **merge:** Join two or more development histories together
 
 # To set-up SSH connection
 
 Follow the [repo](https://github.com/FatemaZahra/github-ssh-setup) or use the [video](https://testingcircle-my.sharepoint.com/:v:/r/personal/fzahra_spartaglobal_com/Documents/Microsoft%20Teams%20Chat%20Files/Github%20setup.mov?csf=1&web=1&e=8FloCR)

