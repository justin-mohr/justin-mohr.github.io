---
layout: about
title: Moopmsg
permalink: /moopmsg/  
---


Often times I find myself waiting on large Stata do files to run. In Python, I like to check the status of my code using a Telegram bot. It allows me to know imediately if a long running script has finsihed or hit an unexpected error. Stata does not easily have this fuctionality. 

I wrote this  program for Stata. It is easily called in your do file. It can send any string message and small files to your Telegram. You will need to make a bot and supply the API token from Telegram

To download 
~~~
net install moopmsg, from("https://raw.githubusercontent.com/justin-mohr/moopmsg/main")
~~~


For more details on about moopmsg and its syntax
~~~
help moopmsg
~~~

I have found it quite helpful and hope you will as well! (Please email me if you encounter any issues)


