#### To get Git Version
```
$ git --version
git version 2.7.4
```
#### After signing up in the gitlab , to configure username
```
$ git config --global user.name "username"
```
#### To configure email address
```
$ git config --global user.email "tuttu.777@gmail.com"
```
#### To check whether the username is set up correctly
```
$ git config --global user.name
tuttu7
```

####  To initalise git
```
$ git init
Initialized empty Git repository in /home/tuttu/Gitlab/myfirstproject/.git/
```
#### To see the status

```
$ git status
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)
```

```
$ touch readme.txt




$ git status      
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.txt

nothing added to commit but untracked files present (use "git add" to track)
```

#### Adding a file to the repository
```
$ git add readme.txt


 git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.txt
```

####  To commit a change 

```
$ git commit -m "myfirstcomit"
[master (root-commit) ab75c92] myfirstcomit
 1 file changed, 0 insertions(), 0 deletions(-)
 create mode 100644 readme.txt
 ```
 
 #### To push the change to the master branch
 
 ```
 $ git push -u https://gitlab.com/project400/my-first-project.git master
Username for 'https://gitlab.com': tuttu7
Password for 'https://tuttu7@gitlab.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 210 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://gitlab.com/project400/my-first-project.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from https://gitlab.com/project400/my-first-project.git.
```
