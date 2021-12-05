# What is git ?

```
Git is a version control system that helps you keep track of changes in your project. 
It is open source and distributed. Git can keep track of the smallest of changes, no matter how large your project is.

 ```
 
 # What is Github ?
 
 ```
GitHub is a Git repository hosting service. 
GitHub also facilitates with many of its features, such as access control and collaboration.
It provides a Web-based graphical interface.
 ```
# Git vs. GitHub: What's the Difference?
```
Git vs. GitHub in Simple Terms is  

Git is a version control system thats lets
you manage and keep track your source code history
And Github is a cloud-based hosting service that lets you manage 
Git repositories.

```
# Install Git 

### Linux :

```
sudo apt-get install git
```
### Windows :
```
Download the latest Git for Windows installer :)

Link : https://git-scm.com/

```
## Now open your terminal  to Verify the installation was successful by typing
```
git --version
```
# Configure your Git :

### Configure username :

```
git config --global user.name "Dark Hunter"
```
### Configure Email :

```
git config --global user.email "darkhunter@example.com"
```
### Show git username :

```
git config user.name
```
### Show git email :

```
git config user.email
```

### You can also use  this command

```
git config --list
```



# Create a git folder :

### Create a folder using 
```
mkdir basic git
```
# now create a file 
```
touch day1.txt

and type :
git init

```
### now check :

```
ls -a
```
### check github status :
```
git status 
```
  
And you will show a  error message and that is  :  

```
No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        day1.txt
        
        
nothing added to commit but untracked files present (use "git add" to track)

```



