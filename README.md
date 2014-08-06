#LilaMarty.com

This site is built using the static site builder Jekyll. It makes things a lot easier after you get started with it, and it helps keep the code DRY (don't repeat yourself).

##Getting Started
The first thing you need to do is install the Jekyll gem. To do this open the terminal application on your computer, and in the prompt copy & paste the following and hit enter:

	gem install jekyll
	
That's it! Now Jekyll is installed on your machine.

Next you need to navigate to your site on your machine. To this, copy & paste this into the terminal prompt and hit enter:

	cd ~/Sites/lilamarty.com
	
To double check that you're in your site's directory, go ahead and type '<code>pwd</code>' into your terminal prompt and hit enter again. You should see something like this:

	/Users/youruser/Sites/lilamarty.com
	
Now you need to start the web server locally on your machine. Again, we use a terminal command to do so:
	
	jekyll serve --watch
	
The '<code>--watch</code>' option flag will keep Jekyll building the site files and watching your changes.

If that starts with no error messages, you can type 'localhost:4000' in your browser, and... **BADDA-BING BADDA-BOOM**, there's your site!

##Deploying
After you've made all your changes, one simple command is used to deploy it to your web server. But first, we need to install another gem. Copy & paste this into your terminal and hit enter:

	gem install glynn --source http://gemcutter.org
	
This will install the glynn gem. After it installs, make sure you're still in your site's directory, and simply type '<code>glynn</code>' into the terminal prompt and hit enter. You'll see glynn doing somethings and building the site. After it's finished, it'll give you the message that it sent the site successfully. Navigate your web browser to your site's address to confirm. That's it!