How to Set up this and other Github Repos on your Computer:
Installing Git:
  1. download Git: https://git-scm.com/downloads
  2. all default settings but make sure it's installed onto path
Preparing for the Repo clone:
  1. find a space for the repository on your computer, (just a folder where you like everything for the repo to be) or you can make a new folder.
  2. make a different folder for different repos.
  3. open the folder
  4. open Terminal inside that folder (on Windows just click on the adress bar of the file explorer and type git then enter)
  5. now clone the repository: Write: "git clone <repository-url>" and hit enter, the url is on the main page of the repo on github, click on the green "Code" button. there you can copy the link.
  6. once you have done this you can move inside the repository folder:
	1. In the terminal type: "cd repoName" and hit enter (the name is the name on the frontPage of the github)
Keeping your local repository synched with the online version:
  1. Before you start changing the local repository on your computer (before coding, changing files, adding files) open the terminal in your repo folder. this is the folder with this readme.txt file
  2. type: "git pull" press enter, (this pulls the newest version from github onto your local machine)
  3. after that you can make your changes
  4. after finishing everything for the day:
	1. enter in terminal still in the repo folder: "git add ." to add all changes or "git add <"yourrepo\filepath\filename">" most of the times "git add ." will be fine
	2. enter in terminal: "git commit -m "write short description here what you did""  Enter for example: git commit -m "wrote the readme.txt file"
	3. enter in terminal: "git push"
  5. now it's done
There's way more to it, but for the beginning this works just fine and will do for 95% of interactions we need to do with github