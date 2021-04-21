# Git-Commands
## Setting Credentials

Sometimes you need to configure username and email – this is great for when you’re working on a team project in the same repository and want to distinguish between who is making the commits and the changes. You would use the following commands:

> git config --global user.name “YOUR_NAME” 
> git config --global user.email "YOUR_EMAIL"

## Making branches and changing branches

To see what branch you're on:
> git branch

To make a new branch:
> git branch branchname

To change branch:
> git checkout branchnametochangeto


## Add, Push, Change

Once you have made a change:
* Add the change in a stage ready to be committed
* Commit the change
* Push the change

The following commands will do this:
> git add .
> git commit -m "message describing what change has been made"
> git push 

Sometimes you might see a message about setting the branch to origin, so just copy the command that it shows on the screen, which looks something like this:
> git push --set-upstream origin branchname

## Using the VIM editor

To change a file in the terminal/command line, in linux you can use the VIM editor. 
To open the file to change, type in the following (replacing filename with the name of the file)
> vim filename

It will open the file in read only mode. To go into edit mode (or insert mode), press i
Now, make your change.

To exit insert mode, press esc

To save a change
> :wq then press enter

To quit without saving 
> :q!


