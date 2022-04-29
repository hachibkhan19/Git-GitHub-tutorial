# Git-GitHub-Tutorial
Here we will be discussing Git and GitHub.  

# Trying to do something new. If you are new to git and GitHub then you can learn from here.

# Setup and configuration
Here we discuss how to install git in ubuntu. We can easily install git in ubuntu if we follow some steps.  

Setp1: run the below command in your terminal for updating os and package.  

```
$ sudo apt-get update 
```
Setp2: We can easily install git in ubuntu if we can run just oneline command.  

```
$ sudo apt-get install git-core
```
A few seconds later you can see press 'Y' for confirming the installation, Please press a 'y' button. You can see git is installed successfully, And it is ready for use.

Setp3: Now you can check it is installed or not, running the below command.
```
$ git --version  
```
You will see git version 2.33.1, yes you have done.  😊  

Step4: Let's go now we will see how to configure with git globally.Please run the below command.
```
$ git config --global user.name "your-username"  
```

```
$ git config --global user.email "your-email"  
```
Now we have successfully registered with the version control system.

Step5: Check it is done or not. Please run the below command.

```
$ git config --list
```
You will see something like this.

user.email=your email(mike@gmail.com)  
user.name=your username(mike)  

`Yes, we have done successfully install and configured it. Now take some rest` 😄

# `Git init`
```
$ git init
```
Git init command used to create a local repository.If we want to create a blank repository in your project then enter a command $ git init. It's create subdirectory .git and it is hidden, It you want to see, just like an enter a command in below, then you see a hidden file like as .git.

```
$ ls -a
```

Now we can create and add files to this repository.
```
$ touch example1.txt
```
This command creates a file like example1.txt in your folder. If you want to edit this file, please open a file in your favorite code editor, I am using VS code.

```
$ code .
```
This command easily opens your file in VS code. Now you can edit this file.

# `Git Status`
```
$ git status
```
The status commands display where are you changing in these files.

# `Git Add`
```
$ git add .
```
This command adds all files from the working directory to the staging area.

```
$ git add filename
```
This command adds single file from the working directory to the staging area.

```
$ git add -A
```
This command behaves like as $ git add .

```
$ git add *.txt
```
If you have many files as the same extension then you can use it easily

```
$ git restore --staged <filename(example1.txt)>
```
If you want to go from the staged area to the unstaged area then you can use it. 

```
$ git restore <filename(example1.txt)>
```
If you want to go from the staged area to the unstaged area then you can use it. 

# `Git diff`
```
$ git diff
```
If you want to see what we are changing in this file we can use it. 

# `Git commit`

```
$ git commit -m "message"
```
Git commit turn files from staging area to local repository. And the message should be clear.

# `Git uncommit`

If we are commit in this file and a few moments later you are thinking it's not perfect we can easily uncommit it. We uncommit it 3 ways.

# `Git reset --soft HEAD^`
```
$ git reset --soft HEAD^
```
If we are changing a recent commit then we can use it.

# `Git reset HEAD^`
```
$ git reset HEAD^
```
If we are changing a recent commit and we try to remove it then we can use it.

# `Git reset --hard HEAD^`
```
$ git reset --hard HEAD^
```
If we want to remove all the commits then we can use it.

# `Git log`

```
$ git log
```
Git log shows all the histories of commits.

# `Git log --oneline`

```
$ git log --oneline
```
Git log --oneline shows all the commits in a simple way.

# `Git show commit_id(839cbea)`

```
$ git show commit_id(839cbea)
```
Git show id() show a single commit.

# `Git checkout commit_id(839cbea)`
```
$ git checkout commit_id(839cbea)
```
Move one commit to another commit.

# `Git remote`
```
$ git remote
```
We can use this command for checking it's connected between a local and remote 

# `Git remote -v`
```
$ git remote -v
```
This command shows the details.

# `Git push -u origin main`
```
$ git push -u origin main
```
This command pushes all files in the remote repository.

# `Git push -u origin dev`
```
$ git push -u origin dev
```
If we create a new branch and want to pushes all files in new branch for this we can use git push -u origin dev(branch name).


# `Git pull`
```
$ git pull
```
Git pull caught the all changes from the remote repository to the local repository

# `Git branch`
```
$ git branch
```
We can check branch using this command.

# `Git branch create_branch(dev)`
```
$ git branch dev
```
If we want to create a new branch then We can use this command.

# `Git checkout dev`
```
$ git checkout dev
```
If we want to switch one branch to another branch then we can use this command.

# `Git branch -d dev`
```
$ git branch -d dev
```
If we want to delete this branch then we can use this command. But we need to switch to another branch then we delete this branch.

# `.gitignore`
All the secrect files or folder are includes in here

# `pwd`
```
$ pwd
```
If we want to see where we are working we can use this command, pwd (Present Working Directory).

# `cd`
```
$ cd
```
Cd (Change Directory) this command is used for changing one directory to another directory.

# `ls`
```
$ ls
```
The ls command is used for showing files and directories.

# `rm -rf (folder_name)`
```
$ rm -rf (folder_name)
```
This command removes a directory.


# `MarkDown`
# `<--comment-->`
<!--comment-->

# `--- Horizontal`
---


<p>I am a paragraph</p>

# `_Italic_`
_This is a italic_

# `__Strong__`

__strong__

# `~~Delete~~`
~~This is a delete~~

```html
<html>
 <head>
    <body>
        <h2>Hello</h2>
    </body>
 </head>
</html>
```

```javascript
    console.log('Hi')
```

# `Order List`
1. item 1
    1. item 1
2. item 2
3. item 3

# `Unorder List`

- item 1
    - item 1
- item 2
- item 3

# `Link`
https://www.google.com

# `Disable Link`
`https://www.google.com`

# `Image Tag`
![This is image](./download.jpeg)

# `Emoji`
😊

# `Table syntax`

|  Name        | Email    |
| -----------  | ---------|
| Hachib       | Hachib@gmail.com |


| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |


