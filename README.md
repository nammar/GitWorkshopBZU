# GitWorkshopBZU
In this workshop we will learn basic git commands both through the GUI provided by the GithubDesktop and the command line.

# common mistakes
1. People misuse github by treating it as Google drive for example. Unlike google drive, github is used for source version control and team work. Thus, avoid committing zip files of projects, commit .java files instead.
2. People should synch before committing 
3. do not commit binary files (e.g., .class files in bin directory in Elipse), .classpath, .project, system specific files and libraries (e.g. JDK) 

# Installation instructions 
1. Create a Github account through web version
2. install Github desktop
3. install Github for eclipse plugin
https://eclipse.github.io

# Basic commands/steps:
## Github Web version:
1. Add a new repository
2. Add collaborators
3. commit

## command line
1. git init: initialize an existing directory as a Git repository
2. git clone [url]: clone a github remote repository
3. git status (working directory vs. remote (master branch))
4. git pull (update)
5. git add [file] (staging files in preparation for commit)
6. git add . then git status
7. git commit -m "messages": to prepare commits
8. git push: to push commits
9. git log: history of commits

## Github desktop version
1. Clone a repository to a local folder 
2. Upload files
3. synch remote repository with local folder

## Git plugin for IDEs (Eclipse)
1. import a project in Eclipse by cloning a git repository 
2. synchronize perspective 
3. commit changes, add to index to stage files, 

# Advanced (another session)
## Git plugin for Eclipse 
1. create a repository from an existin project: 
..* team share project
..* repository perspective remotes>create remote>
..* then commit 
..* http://stackoverflow.com/questions/17552457/how-do-i-upload-eclipse-projects-to-github

## resolve conflicts in Web, Desktop, and Eclipse
 http://stackoverflow.com/questions/21559119/how-to-resolve-conflicts-in-egit
## create a branch
1. start a pull request
2. test and accept/merge with master

# misc
1. how to link it with other apps
2. get mobile notifications
3. slack: https://slack.com
4. enable email notifications

# useful links
1. https://guides.github.com/activities/hello-world/
2. https://education.github.com/git-cheat-sheet-education.pdf
3. http://wiki.eclipse.org/EGit/User_Guide#Index
4. http://help.eclipse.org/mars/index.jsp?topic=%2Forg.eclipse.egit.doc%2Fhelp%2FEGit%2FUser_Guide%2FReference.html
5. https://www.youtube.com/watch?v=BH4OqYHoHC0
