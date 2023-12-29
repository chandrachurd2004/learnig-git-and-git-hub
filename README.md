GIT COMMAND 


                note:
                    different branch can create different pull request to the same repository



git status 
    to see the file which one are tracked by git or not

git add <filename>
    to add the file for tracking
            git add .  -> to add all the file in the current directory

git restore --staged <filename>
    to remove the file from tracking (condition it should be in staged not commited)

git restore <filename>
    if changed bymistake then take it to the orginal position (i.e. to last commited);

git commit -m ".....messages..."      (-m : message)
    to commit the file and save with message as given

git log
    to see the history of the commit

git reset <......commit hascode copy and paste......>
    to restore the previous version of your code

git stash
    to move the changes to a temp places without commit  (i.e. only work with non commited item BUT SHOULD BE IN STAGED AREA)

git stash pop
    to bring stash item

git stash clear
    to clear stash item

git remote add <...costom  name of the connection ...> <...url....>
    to connect your local reposistory to the github/gitlab etc
                git remote add origin git@github.com:chandrachurd2004/learnig-git-and-git-hub.git

git push <......costom name of the connection .....> <...branch name that you wanted to upload ..>
    to push the branch and create pull request
                    note:- each branch will create new pull request

git push <......costom name of the connection .....> <...branch name that you wanted to upload ..> -f
    to push the branch and create pull request forcefully

git pull <....costom name of the connection of the main repo (generally upstream ).....> <.....branch.....>
    to keep in sync with the main repo with your forked repository

git remote -v 
    to see the connections of our reposistory

git branch <.....costom name of new branch ......>
    to create new branch

git checkout <....name to the branch .... >
    to change the current working branch to any branch we wanted

git checkout <.....name of file ......>
    to restore the content of file(i.e. used to restore the previous content of file and delete unwanted and modified content of file)
                note:- a file name as a.txt which is in staging are but u modified it and now u wanted the content of the file which is in stating area (i.e. u wanted to delete the modified content) then use is command , this will delete the content of file and update to the file in staging area  OR  if file is not in stating area then to the last commited file 

git merge <...name of the branch ..... >
    to add file of that branch to the current working branch

git clone <.....url......>
    afte forking the url(i.e. url from your git hub account) need to be pasted here (condition after cloning)
