After adding git to a folder sign in your email credentials.

To add name and email address to git use the command:
git config -- folowed by mail details


ACE_ME@ACE-ME MINGW64 ~/Desktop/myapp
$ git init
Initialized empty Git repository in C:/Users/ACE_ME/Desktop/myapp/.git/

ACE_ME@ACE-ME MINGW64 ~/Desktop/myapp (master)
$ git config --global user.name 'Moses Esumei'

ACE_ME@ACE-ME MINGW64 ~/Desktop/myapp (master)
$ git config --global user.email 'archer.me24@gmail.com'

git rm(removes file from staging area)
git rm --cached index.html
rm 'index.html'

ACE_ME@ACE-ME MINGW64 ~/Desktop/myapp (master)
$ git status
On branch master

No commits yet

# ///////////////////////

$ git add *.html
* - means all in git
The above adds all .html files to the staging area.

# ////////////////////////
To add all file types to the staging area:
- git add .


# ///////////////////////
GIT STAGES
1. Add git to project.
2. Staging(.git add)
3. Commit (git commit)
3a. In new window
i. Click on the  letter "I" to enter insert/edit mode. 
ii. When done, press "ESCAPE".
iii. :wq and hit enter to return to previous screen.

A short hand for committing files after staging to avoid the new po-up window
$ git commit -m 'updated app.js'

/////////////////////
.GITIGNORE
This is used to hide files 