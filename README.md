practiceTime
============

Practice for upcoming projects

Test commit - Gene

Please, feel free to make a branch, make changes, commit them, push and pull request to your liking.  This repository is meant for you to use to practice.

###Tutorial for using git in Ubuntu.

I personally recommend using github on a linux machine, for most projects.  

If you don't have a computer that runs it, you can find VirtualBox to run a VM, and the Operating System Ubuntu for free download on the internet.

For those who don't know, a basic work flow using git in ubuntu goes like this:

* update code by pulling the code from the branch  (in this example master)
	
		git pull origin master

* think of something to fix, fix it, then commit.

		git add [files changed]

		git commit -m"fixed what I wanted to"

* The message in the quotes can be anything, but the more descriptive the better.

* Next, when your fix is working satisfactorily, and your changes are commited, push to your personal branch, in this case I'll call it drew.

		git push origin drew

* This pushes your local changes to github's servers.  Now, on github.com/username/repository, you can see your changes within your branch.

* if you feel these changes should be pulled in by another branch, you can submit a pull request.  

* click the green button next to the branch drop-down menu.  It's pretty easy to see.  

* A pull request is essentially saying to someone else, "hey, look what I did! Can you merge my changes into your code?"

* Now, you repeat the process, with a different issue.  

##Git command reference

All commands are prefixed with `git`.   So `status` should be typed into a console as `git status`.  

	status			returns a status of your current working directory, including branch, 
							changes since last commit, and what files are tracked and untracked.

	commit			commits your changes.  Do this often, because you can always reset your code to any commit. 
							do it before, during, and after you change things, even small things.  
					
							should be suffixed with -m"commit message" for clarity. 

	pull				pulls changes from a remote branch into your current local branch. 
							this should be done before you start working, before you push and merge as well.
							syntax: git pull origin master
								where master is the remote branch you're pulling from.

	checkout		changes current branch.
							syntax: git checkout master
								where master is the branch you're switching to.

	branch			returns which branch you're on, as well as which branches you have locally.

\*note that this is not a complete reference, but meant simply as something easy to look at for some basic commands. 
	feel free to edit this to make it better/add more.
	a more complete and accurate reference can be found by running `git help` 
	or `git help [command]` such as `git help checkout` for more in depth help on a specific command.
