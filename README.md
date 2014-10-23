#LilaMarty.com

This site is built using the static site builder Jekyll. It makes things a lot easier after you get started with it, and it helps keep the code DRY (don't repeat yourself).

##Getting Started
The first thing you need to do is navigate to your site in terminal. Open terminal and type this:

	cd ~/Sites/lilamarty.github.io
	
To double check that you're in your site's directory, go ahead and type '<code>pwd</code>' into your terminal prompt and hit enter again. You should see something like this:

	/Users/youruser/Sites/lilamarty.github.io

Next, make sure you have the latest updated version of your site by entering this in the terminal:

	git pull

Now you need to start the web server locally on your machine. Again, we use a terminal command to do so:
	
	jekyll serve --watch
	
The '<code>--watch</code>' option flag will keep Jekyll building the site files and watching your changes.

If that starts with no error messages, you can type 'localhost:4000' in your browser, and... **BADDA-BING BADDA-BOOM**, there's your site!

##Adding Projects
To add a project, just copy an existing file in the _posts folder, and use that as a starting place. All images for the project should follow the same naming conventions as the others. Sometimes you will have to restart the jekyll server to see a new project after you added it. To do this, just hit <code>control + c</code> while the server is running, and then <code>jekyll serve --watch</code> again.

##Deploying
After you've made all your changes, one simple command is used to deploy it to your web server. This is all done through git. Here are the commands in order:

	git add .
	git commit -m 'enter a short message about what update you made'
	git push
	
That's it!!!
