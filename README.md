# computer Fundamentals

# Software Engineering


# GIT HUB SETUP

# STEP: 1 DOWNLOAD GIT FROM LINK AND INSTALL
	https://git-scm.com/downloads

# STEP: 2 CREATE GIT HUB ACCOUNT
	https://github.com/
	
	Remember Email:xyz@gmail.com
		 Password:xyz@123
		 userName:xyz-abc

# STEP: 3 CREATING REPOSITORY AND GIVE NAME 
	CHECK public repository	
	CLICK on Create

# STEP: 4 UPLOADING FILE TO THE GIT HUB

	Prepare One Folder With any Name say 'GitHub'on your local drive say D:/Github/

 1. open command prompt(cmd)
 2. move to the root directory
 3. execute below commands



	
>git init
>git branch -M main
>git remote add origin https://github.com/Nikunj-Java/FirstDemo.git


>git add .
>git commit -m "your msg"

for the very first time it will ask you for authentication

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

>git config --global user.email "you@example.com"
>git config --global user.name "Your Name"


once this is done again use below commands
>git commit -m "your msg"
>git push -u origin main

now for the very first time this will open a browser and ask you for sign in to authenticate, provide your username and pasword and click on authenticate

once this is done you can see that the file is uploaded successfully

refresh your git hub repository


now for the next time use:
[not that you are on your root directory from cmd]
> git add .
> git commit -m "your msg"
> git push -u origin main
