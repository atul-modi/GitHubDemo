Starting with GitHub

The GitHub comprises of two technical term Git and Hub. Git is the Heart of the GitHub. Hub is a command line tool that wraps git in order to extend it with extra features and commands that make working with GitHub easier.Git is used to manage any type of file such as Word Documents or Final Cut Porjects.

Git is an example of version control

Version control is a system that records changes to a file or set of files and helps us recall specific versions later if needed. E.g. Subversion (SVN), CVS etc

It allows you to : 
Revert files or the whole project to an earlier state
Compare changes over time
See who modified what?
Control modifications by collaborators with the permission of admin/owners

Github is a a repository hosting service for Git
GitHub provides a web-based graphical interface that works on top of GIT. It can also be treated as a social platform to share knowledge and work.
It also provides access control and several collaboration features, such as wikis and basic task management tools

Some terms in GitHub which are used whicle working in GitHub.
1. Creating a repo 
Creating a repository for multiple people to work togetherMaster in a repository. This is the final version that is considered ready to use by anybody in the team or outside if repository is public.

2. Creating a Branch 
Create a branch in your project, for an environment where you can try out new ideas.
Changes you make on a branch don't affect the master unless pull request is accepted.
Changes committed to branch reflects for you to keep track of different versions	

3. Adding Commits
Keeps track of your progress as you work on a branch or master.  
Creates a transparent history that others can follow to understand what you've done and why. 

4. Forking a repository
It creates a copy for you to work on independently without any changes to theirs. 
Submit a pull request to owner so that the owner can incorporate changes.



Working with GitHub:
1. Signup in https://github.com/ 
2. Create a new reposotory.
3. Create / upload the project.
4. Commit it.

Sharing your reposotory for group project.
Navigate to the repository on Github you wish to share with your collaborator. 
1. Click on the "Settings" link in the right side menu, below "Network" 
2. On the new page, click the "Collaborators" menu item on the left side of the page.
3. Start typing the new collaborator's GitHub username into the text box.
4. Select the GitHub user from the list that appears below the text box.
5. Click the "Add" button.

GitHub with local files
1. Install Git https://git-scm.com/downloads
2. Right Click local directory-> open GIT Bash, enter the following command.

git init
git remote add origin https://github.com/manshu-dixithi/JECRC-Management.git
git pull origin master
git checkout -b yourname
/* Modify The Code*?
git add *
git commit -m "Changes That You Have Made"
git push origin yourname
3. Create a Pull Request for the changes by your group members.



