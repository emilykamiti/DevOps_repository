# DevOps Assignment README.


## Note: This documentation  includes:
1. creating a local repository.
2. Adding a README.md file to it.
3. Creating a remote repository on github.
4. Linking the Local and the remote reposiroty
5. Writing down the steps followed in a README.md file created on the Local Repository.
5. Pushing the changes made in the Local to the remote repository.

- Note: You should have a git hub account set up to be able to create a remote repository.
- If not click the link below to follow the steps:
- https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account

## Creating a directory

- Create a directory any where on the local machine
- for example create a directory named (first_repo) on the desktop or any prefered location in your machine.
- The name of your directory should be of your choice.

## Initialization

- On your terminal (Visual Studio Code terminal) navigate to newly created directory.
- For example if it was created on the desktop , it can look like this (./desktop/ first_repo.)
- Your current directory should be the newly created eg first_repo.
- Type the command Below in the current directory.

###### (git init) to initialize the local repository

## Add a README.md file

- Add the a README.md file by: 

- - Manually by right clicking on the directory/ first_repo and then choose option file and enter file name as README.md
- - Or type command (notebook README.md ) to write documentation/steps on notebook editor
- You can replace notebook editor with any other editor of your choice.

- Write down the Steps in the REAME.md and  click save..

## Type follow up commands

- - git add README.md, to add file.     
- - git commit , enter commit message, save and exit editor.

## On your github

- Make sure you have  a git hub account, if not follow the steps on the link provided at the beginning.

- Create repository by clicking new.
- Enter the name of the repository eg myfirst_repo.

- click on SSH and copy Url.

- Return to terminal and enter the command
 - - git remote add origin <repository_url>
 - - git push -u origin master

#### Note: The README.md file can be updated and changes commited and pushed to the remote repository






