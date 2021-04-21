# Git-Commands
## Setting Credentials

Sometimes you need to configure username and email – this is great for when you’re working on a team project in the same repository and want to distinguish between who is making the commits and the changes. You would use the following commands:

To set a username
> git config --global user.name “YOUR_NAME” 

To set an email
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

add change ready to be committed
> git add .

commit the change
> git commit -m "message describing what change has been made"

push the commit
> git push 

Sometimes you might see a message about setting the branch to origin, so just copy the command that it shows on the screen, which looks something like this:
> git push --set-upstream origin branchname

## Merging a change into another branch
Say you have a branch called branch1 and you want to merge it into the master branch, you would do the following
* Go into your master branch
* Fetch the branch1
* Merge the branch1 into master

You should know how to go into master branch now, then to fetch branch1, type in the following:
> git fetch origin branch1

Now, to merge into master, type in the following:
> git merge origin/master
## Using the VIM editor

To change a file in the terminal/command line, in linux you can use the VIM editor. 
To open the file to change, type in the following (replacing filename with the name of the file)
> vim filename

It will open the file in read only mode. To go into edit mode (or insert mode), press i.

Now, make your change.

To exit insert mode
> press esc

To save a change
> :wq then press enter

To quit without saving 
> :q!


