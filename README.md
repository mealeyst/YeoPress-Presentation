#About the Yeopress Presentation Project
##The cool way to kickstart your Wordpress Project

This repository has been set up as an educational repository for those looking
to learn about what Yeoman has to offer. This repo contains two major parts a
presentational repo (built using [reveal.js](http://lab.hakim.se/reveal-js/#/)
and [Yeoman](http://yeoman.io/)), and a bare bones site repository that also 
happens to be its own repository found: [here](www.example.com) and contains
instructions on how to get a working Wordpress site up and running.

_(Note: You should have some experience with both Github as well as the Command
Prompt <Windows> or Terminal <Unix>)_

#How to install reveal.js and view the slides

To be able to view the slideshow for this repository there are a couple tools
that you need to have installed and in just a few simple commands, the
presentation will be viewable right on your machine. 

The good news is, Option 1 downloads the same tools you'll need for the 
[Yeopress Example](www.example.com) repository!

_(Note: There are two optional paths you can take to view the slides, though I
would suggest using option one as it installs Yeoman, which is used in the
accompanying Yeopress Example repository)_

+ ####Install Node
	- Navigation to the [Downloads Page for Node](http://nodejs.org/download/)
	and install the version that matches your operating system. 
	_(Note: You can also install Node.js by cloning their repository from:
	[here](https://github.com/joyent/node) and follow the installation
	instructions for your operating system, though I would only recommend this
	option to advanced users.)_
- ####Install Grunt
	+ With your Terminal or Command Prompt still open, enter the following:
	```npm install -g grunt-cli```

+ ####(Option 1:) Install Yeoman
_(Note: If you choose Option 1, you can disregard Option 2)_

	- Open either your Terminal or Command Prompt and enter the following
	```npm install -g yo```
	
+ ####(Option 2:) Install Bower and Grunt
_(Note: If you choose Option 2, you can disregard Option 1)_

	- ####Install Bower
		+ Open your Terminal or Command Prompt and enter the following:
		```npm install -g bower```


+ ####Set up the slideshow!
	- With your Terminal or Command Prompt still open, navigate to the directory
	that you cloned this repository to.
	- Run the following commands while inside of the 
	`<root>/yeopress-presentation` directory:
	```npm install && bower install```
	_(Note: If you you just cloned the directory from github without changing 
	the directory name, it should look like: 
	`YeoPress-Presentation/yeopress-presentation`)_

+ ####View the Slideshow!
	- With your Terminal or Command Prompt still open and while still in the
	same directory, run the following command:
	```grunt serve```
	The slideshow should now load up on your default internet browser!


