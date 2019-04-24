# Git/Github Tutorial (Correct use/Installation) #

### Note Before Starting
1. You will be using the Command Prompt (Windows) or Terminal (MacOS/Linux) to run most of these commands! I recommend tagging these application to your Applications bar or somewhere to where you can easily access those applications.

2. **YOU CAN EDIT YOUR CODE WHEREVER YOU WANT!** But, to use Git you will have to use the command line to make commits and push them to GitHub.
### Installing Git
1. Follow the tutorial [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) based on the Operating System running on your computer (i.e. MacOS, Windows, Linux). 
**Note For Windows Users: Install the first link in your instruction section which is called "Git for Windows"**
2. Check you installation worked by going to your command line/terminal and typing the command below.
```shell
git --version
```
Note: If you get an error that "git" is not a command, that means your installation failed and you need to try again. If your second attempt does not work, EMAIL ME! I will help you troubleshoot.

## Using Command Line

Command line is sometimes cumbersome to those who are new to it. But, all you are doing is looking at your file system and typing commands to do things you are used to using a User Interface for. Here is a quick cheatsheet to help you learn some basic commands. Feel free to Google other commands if you are interested in doing more complicated things/ I don't explain something you need!

###### Listing Files in a Folder/Directory
Mac/Linux:
```shell
ls
```
Windows:
```shell
dir
```

###### Changing Folder/Directory
Mac/Linux/Windows: 
```shell 
cd name_of_file
```
Note: To go to the previous directory use name_of_file as ``` .. ```

## Using Git

Git is an amazing program for version control of your Apps (or any Application for that matter). You will need to use the Command Prompt/Terminal to push, pull, and commit changes to GitHub. Here is a helpful cheatsheet on how to use Git.

##### Step 1) Setting up a Local Repository
**YOU MUST DO THIS WHEN YOU START ANY PROJECT! YOU ONLY NEED TO DO THIS ONCE PER PROJECT!**
1. Open Command Prompt/Terminal and navigate to the directory (folder). I recommend just using the default opened folder if you are new to Command Line Interfaces. You can navigate your file system with the command line tips above. 
2. Go to you Command Prompt/Terminal and type the command below, BUT DO NOT HIT ENTER YET!
```shell
git clone
```
1. Go to GitHub and in your repository click the green button that says ```Clone or Download```. Copy the URL into your Command Prompt/Terminal and now hit ```Enter```. This will setup your repository. Make sure you're copying the link for ***HTML***.
Note: Your command will look something like this: 
```shell
git clone https://github.com/...my_repository
```

##### Step 2) Creating Commits
**YOU SHOULD DO THIS STEP EVERY 20-30 MINUTES!!**
Commits are what create your messages so that Dr. Riedel can see your changes. You should do this, in all honesty, when you get a big change working in your code. To create a commit with a message, use the commands below in your Command Prompt/Terminal, while in your Git repository (folder/directory with all of your code on your computer).
**Command 1:**
```shell
git add .
```
**Command 2:**
```shell
git commit -m "put your commit message here"
```

##### Step 3) Pushing your Commits to GitHub
**YOU MUST DO THIS TO SEE ANY CHANGED ON GITHUB!!**
You can do this whenever you want. You can have any amount of commits before doing this, because Git will know how to handle it. You simply type the command below in your Command Prompt/Terminal, while in your Git repository (folder/directory with all of your code on your computer).
```shell
git push
```

##### Step 4) ONLY if you Edited Something on GitHub
You need to pull down your changes you don't have a discrepancy between the code on GitHub and the code on your computer. You simply type the command below in your Command Prompt/Terminal, while in your Git repository (folder/directory with all of your code on your computer).
```shell
git pull
```