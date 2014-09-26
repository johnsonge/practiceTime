practiceTime
============

Practice for upcoming projects

Test commit - Gene

Please, feel free to make a branch, make changes, commit them, push and pull request to your liking.  This repository is meant for you to use to practice.

###Tutorial for using git in Ubuntu.

I personally recommend using github on a linux machine, for most projects.  

If you don't have a computer that runs it, you can find VirtualBox to run a VM, and the Operating System Ubuntu for free download on the internet.

For those who don't know, a basic work flow using git in ubuntu goes like this:

	update code by pulling the code from the branch  (in this example master)
		
			git pull origin master
	
	think of something to fix, fix it, then commit.

			git add [files changed]

			git commit -m"fixed what I wanted to"

	The message in the quotes can be anything, but the more descriptive the better.

	Next, when your fix is working satisfactorily, and your changes are commited, 

	push to your personal branch, in this case I'll call it drew.

		git push origin drew

	This pushes your local changes to github's servers.  Now, on github.com/username/repository, you can see your changes within your branch.

	if you feel these changes should be pulled in by another branch, you can submit a pull request.  

	click the green button next to the branch drop-down menu.  It's pretty easy to see.  

	A pull request is essentially saying to someone else, "hey, look what I did! Can you merge my changes into your code?"

	Now, you repeat the process, with a different issue.  
