git config > command to configure the repository. 
git add > command to use to add files to a git project, adds them to the index file so that they can be tracked in the staging area.
git status > can be used to see what files are in the staging area (not commited yet). 
git status -s > view the output in shortened format 
git status -v > get more verbose output, including what was changed in a file 
git rm > removes a file from a project 
man git-status > local documentation for the git statis command 
git commit > opens text edito to prepare for a commit of files in the staging area 
git commit -m "message" > bypasses the editor and performs a commit with the specified message
git commit -a-m "message" > commit a modified file in the staging area 
man git-commit > local documentation for the commit command 
 git .git/info/exclude > original file that contains file patterns tha git will not track 
.gitignore > ignore gile local to a git repository commonly used to exclude files based on patterns. 
git check-ignore <pattern> > used to debug git ignore to see what is and is not being excluded from git. 
man gitignore > local documentation for the gitignore file 
git tag -a <tag name> -m <message> > create an annotated tag 
git tag > view all tags for the repository 
git tag <tag name> -m <message> > create a lightweight tag 
git tag -d <tag name> > delete a specific tag 
man git-tag > local documentation for the git tag command 
git show <tag> > shows information of an specified tag 
git branch <branch name> > creates a new branch of the project tree 
git checkout <branch name> > switches to another branch 
HEA> pointer to the current branch being worked on, can use git log and git status to view which branch HEAD is pointing to 
man git-branch > local documentation for the git branch command 
man git-checkout > local documentation for the git checkout command
git merge> combines the latest commits from 2 branches in 1 branch
git branch -d <branch> > deletes specifed branch
man git-merge > local docs on using the git merge command
git rebase <branch> > replay changes made to one branch over the top of another branch
man git-rebase > documentation for the command
small change
git revert <commit> > revert a commit in the project
man git-revert > local documenation on using the git revert command
git diff > view the differences between 2 commits, files, blobs, or between the wotking tree and the staging area
man-git diff > documentation for the command
git gc > the git garbage collection command, cleans out old objects that cannot be referenced by the db anymore, and compress the content within the .git directory to save disk space
git gc --prune > by default, cleans out objects that are older than 2 weeks
man git-gc > documentation
git log > view the git repository history
git log --graph > show a textual graph of a projects commit history
git log --stat > show statistics of the files with each commit
git log ==prety=format: format the output of a git log command to display specific fields
man git-log > local documentation on using the git log command
git clone <local repo> <ner repo> > clones a local repository to a new repository on the local file system
man git-clone > local documenation for the clone command
git clone <Remore url> > clo nes a remote git repository to the local file system
git remote -v > shows the remote servers that are being tracked for the current repository and their latest statistics
git fetch > fetches new commit information down from te remote server for the current repository, does not commit anything to the local db
man git-fetch > documentation
man git-remote > documentation

