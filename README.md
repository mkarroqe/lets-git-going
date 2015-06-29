# lets-git-going
This was written by [Liza Ramo](http://github.com/LizaLemons), my mentor at the Global Fund for Women's Ignite hackathon.  Thanks Liza!
##Using GitHub:

- Almost all developers use GitHub every day on the job to collaborate with teammates 
- You guys are developers! Time to learn Git & GitHub! 

Remember the picture on the whiteboard! 
https://twitter.com/LizaRamo/status/566672394165964800



Steps: 
1- Make changes to your code in Sublime Text
2- In your Terminal, navigate to the Gray Spaces folder
3- Type the commands: 
		git add . 
	and 
		git commit -m "Type a little note here about what you worked on in the code"

	--> This will "add" your new changes to your invisible .git file 
4- Now, type in: 
		git push origin master
	--> This will "push" your new code you just worked on to your repository on GitHub 



Pulling from github.com to get your teammates' latest code:

- In your terminal, type in:
		git pull origin master



Fixing Merge Conflicts!! 

Here's a brief guide that explains everything really well: 
http://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging#_basic_merge_conflicts

- If you get an error that says there are "merge conflicts", don't be scared. Open up the file where it says there are conflicts, you'll find weird typing that looks like this:

		HEAD >>>>>>>>>>>>>>>>
		=============

		some code will be here

		>>>>>>>>> 323984709462734029387094870298374

- Basically what you want to do is keep the code that you know is correct, then add, commit and push again. 
- *Note: Merging can be tricky... If you get stuck, have a mentor help you fix it






