# **Instruction for version control at GIT**
## What is Git?

Git this is programm of version control

~ exampal how to make sentence crossline ~

## Initialization of repositoriy
    Git init  is command to reate a version 

to create frame - use tab

to check status of reposetariy

## Adding changes at index 

to add changing at index for next commit need input comand:

    git add <filename>

# **Futher is started home task action 211122**

The task is: to describe few functions of git version control and implement correct saving of new versions of documentation 

* git commit -m - function confirmes saving and adds description of changes into the new version
* git commit -a -m - function allows to implement both comands (add+message) in one click
* git log  - function allows to cause version's consecutive range of changes with description
* git log --oneline - function allows to see descriptions of versions in more accaptable view 
* git log --oneline --all - function do the same action as function git log --oneline 
* git diff - function cause description of versions to see diffirences between actul version and earlier versions 
* git checkout \<hash> - this is special function allows using direct name of earliest version go back to search it 
* git checkout master - function allows to go back from earlier to actual version, after was caused checkout \<hash> function 

<hr>

# Home Task 241122


The task is: to continue actions with earlier seminar's file
1. create and merge at least 4 branches
2. creat and find solutions for conflicts

# Actions with branches at git

## Functions of merging branches
for cases we need to connect two branches available following functions:

+ merge <name>
##### join two hystories of branches together
+ rebase <name>
##### reapply commits on top of another base tip

<hr>

## Possibility to relocate HEAD inside of branch

If we get needs to move from commit to commit following functions are available:

+ checkout HEAD^
##### to mave HEAD point for 1 step down to tree use following command. After action keep in mind do not forget saving pcedures
+ checkout HEAD~num
##### in case we need to move HEAD more then 1 step on tree use HEAD~num function where num is numbers of needed steps
<hr>

## Actions with branches at git

For that to manage by actions with branches of chages should use following commands:

+ branch <name of branch> 
##### for that to create new branch we should use command above. then obligatery execute commit for both branches point of changes. to make sure every thing ok use command git status, git branch, git log and and git log --graph

+ branch -f <name>
##### sometimes we need to relocate branch from parent's commit to another commit point. To achive a goal use <\git branch -f command>. In end of the process do not forget to execute saving steps (see above)

+ branch -d <name>
##### if owner finished developing of child branch he should exports data of last commit to main parents branch. After that owner should delet child branch 
<hr>

## Graphical vision of tree

At the some sitution cold be easer to use graphical properties of git. For instace, if needed to see thr path of branch available following commands:

+ log --graph
##### following command allows to look on short graphical view of one branch
+ log --graph --oneline --all
##### in cases we need to see whole tree completly we should use this one command>

1. master branch

2. added one

3. add info to one 

4. from master add two

5. add info to two

6. add three

7. add info to three

8. start merging 

10. made changes at three 



