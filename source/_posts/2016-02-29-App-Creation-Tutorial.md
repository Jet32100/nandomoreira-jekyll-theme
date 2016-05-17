---
layout: post
title: "Blog Post #4"
date: 2016-04-13 09:39:18
comments: true
description: "App Creation Tutorial"
keywords: ""
categories:
- welcome
tags:
- welcome
---

The app we created was an App that allowed for the user to “click” to have a gif sent to their phone number of choice. The app works using the Twilio API, which allows you to get a temporary phone number. The Giphy Api lets you send GIFs from the phone number assigned from Twilio to the phone number of your choice. Our app was built with a models folder, a public folder, and a views folder. In our models folder was a ruby file called TextRoulette.rb, which was responsible for hooking into the Twilio API, shown in the screenshot below. ![My Helpful Screenshot](/nandomoreira-jekyll-theme/assets/images/code1.png) In our public folder was our style.css file, which used cascading style sheets in order to style our web app. The CSS here is responsible for handling the layout of our web app, but not the actual content contained in the app. The GIF on our web app’s home page is supplied by Giphy. A screenshot is included below. ![My Helpful Screenshot](/nandomoreira-jekyll-theme/assets/images/code2.png)
In our views folder we have the file index.erb, which is responsible for embedding ruby in with HTML. This is required so we can have the commands executed by ruby shown by HTML on our web app itself. A screenshot of our index.erb code is below. ![My Helpful Screenshot](/nandomoreira-jekyll-theme/assets/images/code3.png) Finally, and most importantly is our controller.rb file, which is basically the central hub for controlling all of our other files. In our controller.rb file we reference all the ruby gems we are going to need, including sinatra. Normally, a controller.rb file would contain more code, but since most of our code is being done through the API in the TextRoulette.rb file, ours is pretty barebones. A screenshot of the controller.rb is included below. ![My Helpful Screenshot](/nandomoreira-jekyll-theme/assets/images/code4.png)	
Thank you for taking the time to read through my tutorial, and I hope you can create your own GIF generator soon!