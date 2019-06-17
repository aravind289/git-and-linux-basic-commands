# git-and-linux-basic-commands
basic commands of git and linux to rmemeber
**Command line study:**

1.Creating a new file:
```
$ touch filename
```

2.Display the content of the file:
```
$cat filename
```
3.To create a new folder or directory 
```
$mkdir foldername/directory name
```
4.To goto some other folder
```
$ cd foldername
```
5.To know the root directory
```
$pwd(print working directory
```
6.To display the content in the directory
```
$ls   #(list)
```
7.To return to parent directory
```
$cd 
```
8.Working with files and directory
* To move a file to some folder
```
$mv file name directory name
```
* To rename a file name
```
$ mv old filename newfilename
```
* To copy a file
```
$cp oldfilename newfilename
```
* To copy a directory
```
$ cp -r olddirectoryname newdirectoryname
```
* To remove a file
```
$rm fileto_remove
```
* To remove the directory
```
$rm directory_to_remove
```


**Git commands
Steps to add your project from local to github**

1.To run the git command
```
$git init   #init is for initialize
```
2.To select the file 
```
$ git add filename(this file is file with changes)
```
3.To save the changed file
```
git commit -m “any message”
```
4.We need to create a remote or add the file if the remote is created
```
git remote add remote_name url
```
5.Since the connection is made with the remote , now u have to push the file
```
git push remote_name master
```
6.Now the file is in remote
Now to download in ur computer
 ```
 git pull remote_name master
```
7.To check which files have been modified/also used to know which files has been added and which has not
```
git status
```
8.To visualize where the code has been modified
```
git diff
```
9.After you pull the changed file how to check where the changes have been made
```
git log -p
```



