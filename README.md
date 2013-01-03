# Maintenance Mode: On

![Heroku: Maintenance Mode](http://f.cl.ly/items/0V1i2M182q3q3h1F2P07/Screen%20Shot%202013-01-03%20at%2011.36.44%20AM.png)

**Never show users this screen again**

There's an issue with creating these static maintenance pages, you have to re-write everything from scratch, pull in styles from your app, and push it up to amazon from another repo. Eliminate a few of the steps by starting from a good place and pushing to the freely hosted Github Pages. Here's how to do it.


Installation:

* Fork this repo and make sure to name it specifically for your app
* Change the text, meta information, favicon, and background image
* Push to github under the branch name "gh-pages"
* Get a latte and wait 10 minutes for your page to be live
* Double-check the URL http://gh-user-name.github.com/repo-name
* Once it's live and pretty the way you want it, add the Github Pages URL to Heroku under the settings tab for your app
* Next time you enable maintenance mode on your app, you'll have a gorgeous page ready to make users smile