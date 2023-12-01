'git init' -> power your folder to be managed by git, and intialises
 anew repository. it also create a .git folder that has all the relevant logic to
 manag versions of your project.


    2 'working Area' -> there can be a bunch of files that are not currently handled by git.
    it means that changes done or to be done in those files are not managed by git yet.A files
    which is in working area is considered to be not in the staging area.when we do 'git status'
    and we see a bunch of 'untractted files' then these are actually called to be working area. 

   3. 'staging area' -> what all file are going to be part of the next version that we will create.
    this staging area are the place where git knows what changes will be done from the version to the next version.


   4. 'repository Area' -> this area actually contain details of all you pervious registered version.
    and the files in this area, git alredy manges them and knows  their version history.


    5. 'git add <file>' -> moves files from working area to staging area

    6. git rm --cached <file> -> moves file back from staging area to working area

   7. 'commit' -> commit is a particular version of the project . it catures a snapshot of the project's staged 
   changes  and create a version out of it.

   8. 'git comit' -> registers staging to a comits to acommit

   9. 'git log' -> list down all the comits of the repository. if you want to exit out of git log pront 
   press 'q'.

 10.  'git restore <file>' -> it removes all the files changes from the staging
   area to be commited . tis can be useful , if we did some dirty pice  of code and now no more want it.
   instead of deleting every change line by line , we can restore it or you can say restore last clean version of file.


11. 'git restore --staged <file>' -> it removes file from staging  area to the working area.
this only works if changes are in your staging area

12.diffreance between git rm and git restore 
ans:if you want to move the hole file back to the untractted state , then we do git rm , other wise if we 
just want the chenges to ove in working area or staging areathen we git restore.

13 'git diff commit1 commit2' -> gives the diffreance of all files changes between two commits

14 'git commit -m "<you commit manges>"'-> if we want to avoid opening atext editor like vim/nano to add  commit massage we can use the following command  

15. 'git remorte' -> list down all the remote connection names

16. 'remote connection' -> it helps to link to git repositories for uploding and download
chenches from each otherwise.

17. 'git remote add <name of remote> <link of remote>':this command healps us to a new link to
remote repo and give aname to it.

18. 'git remote rm <name of remote>': this command delete a remote connection

19. 'git remote rename <olname> <newname>': this command renam the remote connection

Note: The name of the remote connection is always use to estabilish comminication between the repositories 

20. 'git add <file1> <file2> <file3>': this command will add  multipule files chenges togather in the staging area

21. 'git add.': this command use to shift all the file from working area to staging area.