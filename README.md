# git-and-linux-basic-commands
basic commands of git and linux to rmemeber
**Command line study:**

1.Creating a new file:
```
$ touch filename
```

2.Display the content of the file:
*$cat filename*

3.to create a new folder or directory 
$mkdir foldername/directory name

4.To goto some other folder
$ cd foldername

5.To know the root directory
$pwd(print working directory

6.To display the content in the directory
$ls   #(list)

7.To return to parent directory
$cd 

8.Working with files and directory
To move a file to some folder
$mv file name directory name
To rename a file name
$ mv old filename newfilename

To copy a file
$cp oldfilename newfilename

To copy a directory
$ cp -r olddirectoryname newdirectoryname

To remove a file
$rm fileto_remove

To remove the directory
$rm directory_to_remove



Git commands
To run the git command
$git init   #init is for initialize

To select the file 
$ git add filename(this file is file with changes)

To save the changed file
Git commit -m “any message”

We need to create a remote or add the file if the remote is created
Git remote add remote_name url

Since the connection is made with the remote , now u have to push the file
Git push remote_name master

Now the file is in remote
Now to download in ur computer
Git pull remote_name master

To check which files have been modified/also used to know which files has been added and which has not
Git status

To visualize where the code has been modified
Git diff

After u pull the4 changed file how to check where the changes have been made
Git log -p




