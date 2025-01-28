## This is a readme file of Git commands which has the below details:
To get the version number                         --> git --version    
To navigate to a specific directory               --> cd <file location>
To initialize the Git repository                  --> git init
Clear Screen                                      --> cls
Diretory                                          --> dir
To set username                                   --> git config --global user.name "Sivakumar"
To set email id                                   --> git config --global user.email "sivakumar291197@gmail.com"
To get the status of Git                          --> git status
To add any files for stage                        --> git add ./git add <file>
To commit any files in stage                      --> git commit -m "This is my first commit"
To get the branch name                            --> git branch
To update the branch name to main                 --> git branch -M main
To assign a Github repository to a local folder   --> git remote add origin https://github.com/Siva291197/Gittutorials.git
To check the origin                               --> git remote -v
To push the files from stage to main              --> git push origin main
To clone our repository to a different local      --> git clone https://github.com/Siva291197/Gittutorials.git
git pull
git pull origin main
Difference of what is changed but not staged      --> git diff
Difference of what is staged but not committed    --> git diff --staged
To get the current branch/list of branches        --> git branch
To create a new branch                            --> git branch <branchname>
To switch from one branch to another              --> git checkout <destination branch>
To merge sub branches to main branch              --> git merge <sub branch name>
To get the history of commands executed in Git    --> git log
To get the last 3 history of cmds executed        --> git log -p -3
To remove a file                                  --> git rm <filename>


Git clone can be used to track any new files that are getting created. However, any changes made in the contents of the existing files will be tracked only in the main location from where it is getting cloned.

Comment added by Developer A

