# GitProject
This is a Demo Git Project Setup Repository

# Markdown File
Where we can write HTML code like in Jupyter Notebook

# Git 

Git is the most important topic as almost all companies use it, as different developers work on the same project, it solved that issue

## Git is a Version Control System (VCS)
- It is used in context of different versions of apps like first version then second version
- To control those versions we need version control, even if single line of code is changed it comes in category of a new version.
- Its managed using Git
- It is open source
- https://git-scm.com/
- To create even the first version, a lot of versions are needed or lines of code are needed (minor versions and major version control)
- A lot of Version Control Systems are available in the market but majority of companies use this
- Different tools came before VCS but they were not effective
- Even if I create version alone, we may not need Git
- If we add feature, where did the previous version came, only upto specific undos can be done, Git records changes at every step
- If we want to create a Student Management System, a lot of features are to be added and every person need to work on a specific part of the project
- For e.g. 
    - Anurag will create Landing Page (even in landing page he will add HTML/CSS)
    - Atharv will add Bootstrap
    - Divya will add JavaScript
    - Divyam will do the Back-End Integration
- Every person will do the work on local system, but ultimately the code should come on a given place, we need to track it, to avoid conflicts at every step.

# Git --everything-is-local (Website)
- Git and GitHub are different things
- Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency
- Git is easy to learn and has a tiny footrpint with lightning fast performance
- It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows
## Companies and Projects Using Git
- Almost all big companies like Google, Microsoft, Meta, Twitter, LinkedIn, Netflix, Camel, PostgreSQL
- Projects Using Git Android, Linux, Rails, Qt, Gnome, Eclipse, K, X
- And various small companies also use it

# Install the Git
Install Git from Website and open Git Bash in Windows
Use git --version to check version

# Create a new folder on Desktop
In Windows you can open terminal from the path line 
In Linux you can do that directly by just a Right Click

## Step 1. git init command
- In the git bash terminal type git init to initialize the git files and empty repository is initialized
- A hidden folder is created by the name .git
- The folder contains various files that contain functionalities like code tracking

## Step2. Configure User (to validate whether the user is authentic or not, git will configure username and email to all files)
Two commands are there 
- git config --global user.name 'Himanshu'
- git config --global user.email 'himanshu@gmail.com'

- All changes performed in the folder, even a . is tracked along with timestamp which can help us create version logs
- If you are working in a team everyone can track the progress

### Staging Area
- All files are being ready to be presented to others (to be kept in a Cross Check Box). Its called Staging Area
- Advantage of Staging Area
    - There might be errors in code, so first you keep it in safe passage( staging area) before you commmit (save) to main project

## Check status using git status
Before that if it throws an unsafe error type
git config --global --add safe.directory 'D:/College/REACT JS Course/Git and GitHub Version Control System/gitproject'

## Master Branch
- Place where actual code is there where there is main product is written
- Everyone is working on a separate branch
- No commits yet implies you have not forwarded the code to show others (like Checkpoint of game, it starts from the same checkpoint)
- Untracked Files is shown when you have not sent any code to staging area (before sharing it to others you keep code there, all code changes are there to create a saved state)
- They are shown in red colours

## To add files to staging area
git add . (represents all)
git add index.html (specific file only)
git add *.html (all html files sent)

## Check Status again
Now files are in staging area, red colour of untracked files changes to green new file word added
If we commit it saves it as a log and saved

- Modifiying Stage (Initial) --> Staging Area
git rm --cached index.html

# Sublime Text Editor
A blank circle represents untracked files 
While Green arrows represents tracked files or in staging area

# GitHub
It is a Code Hosting Service Provider

# SSH (Secure Shell) 
Only authorised user can make changes, there is a very large code, no one can make changes until he has that link

# SSL

It tracks using Hash Code and Time Stamp

Modified --> Staging Area (Buffer Section for Commit) --> Commit (along with message)

CTRL + SHIFT + V works in command prompt
Remote Repositroy is called origin (where it all started)

You tried to paste it using

CTRL + V
before and it didn't work so you went ahead and pasted it with classic

Right Click - Paste**.
Sadly whenever you enter CTRL + V on terminal it adds

a hidden ^?
(at least on my machine it encoded like that).

the character that you only appears after you

backspace
(go ahead an try it on git bash).

So your link becomes ^?https://...

which is invalid.

All things can be done using GitHub GUI as well but we will do it using code, teams do it using code in development teams.

Add README.md files to give details of the repository.