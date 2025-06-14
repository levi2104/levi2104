# git and github full course:

## version control system(vcs)/ source control: 

tracking and managing software code changes, also all the versions of the code i.e circles are versions of code, we can revert back anytime, when we want the previous version of the code if current version is buggy or any other reason

u can see the notes for vcs e.g

## git vcs (not github, its a different thing):

to use vcs on your device, install git

## git setup global configuration:

here, we can setup using cmd given in setup, we can setup email and name to let others know that this line is contributed by me with this name and email while working with git

now, i have created a file index.js in git after changing the directories in cmd and then doing "code ." to open vs code directly from cmd for that particular directory

but, right now, git is not tracking the file index.js, so first we need to initialize git for this project, for that we'll have cmds

## git init:

if u give cmd "git init" in terminal, it enables the git for our current directory, but its not yet started tracking our files i.e index.js


## .git hidden folder:

its a hidden folder which stores all the changes and tracking and all, but we dont need to do anything with it, thats why its hidden

## git add <file_path>:

when u give cmd : git add index.js

it starts tracking index.js

now whatever u add or remove from it, will be tracked by git

if u type : git diff

it gives u the changes history that wt u have added, removed etc

## git add . :

when u do : git add .

it starts tracking all the files in the current directory even if they're inside sub directories/folders

## git remove:

if u want some tracked file to be untracked again, u can do that using :

git rm <file_path>


## commits:

whenver u feel that okay now the changes are complete of lets say any file or folders having multiple files, u do smthin called commit and give a msg like "initial code added" 

cmd : git commit -m "Initial Code Added"


## git log:

by giving this cmd : git log

u can see the commit history, that who has commited? and when? 

and this is : commit e40b9f088af1835906254832f6b140199fe7639c

known as commit id

