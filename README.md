# Electronics-Design-Challenges
## Setup Instructions
Note: all setup instructions are using the terminal commands.
1. Start by cloning this repository with the command.
   `git clone https://github.com/huskyroboticsteam/Electronics-Design-Challenges.git`
2. Move into the cloned folder with `cd Electronics-Design-Challenges/`
3. You will need to create a branch so your work isn't colliding with other people's work. Your branch name should be of the format Firstname-Lastname e.g. Emela-Moreyra. Use the command `git checkout -b branhcname` and put your branch name where it says `branchname`
4. Now you need to make the initial push to set up your branch for everyone to view. Use this command replacing `branchname` with your branch's name: `git push --set-upstream origin brancname` After initially setting your upstream branch you should only need to use the command `git push` to push changes.

Your branch should now be set up and ready for you to take on the challenges.

## Updating Your Branch From Master
When we post new challenges, the specifications document will be added to the master branch. In order to receive the new specifications on your branch you will need to pull changes using `git pull origin master`

## Basic Git Terminal Usage
### Commiting
Make sure you commit your changes often.
1. `git add .` Using this exact command will stage all files for commitment. Optionally you can replace the . with a file name to only commit specific files.
2. `git commit -m "commitmessage"` Use this command to commit all staged changes from the previous command. If you forget the `-m "commitmessage"` a terminal editor will open (VIM) which I cannot help with so don't forget it. Make sure to replace `commitmessage` with a descriptive message about what has changed and **keep the quotation marks.**

### Pushing
1. Follow the instructions to commit all changes.
2. `git push` If you get an error say your upstram is not set then use `git push --set-upstream origin brancname` where `branchname` is where you want to push to, such as master or your design challenge branch.

### Pulling Changes
1. Follow the instructions to commit all changes.
2. Use `git pull origin branchname` where `branchname` is the branch you wish to pull changes from such as master or your challenge repository.
3. You will need to commit these changes again.

## Other Helpful Commands
`git status` Shows you the status of your branch

`git branch` Shows you the list of all branches and highlights which branch you are working in
