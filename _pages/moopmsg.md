---
layout: about
title: Useful Software
permalink: /software/  
---
## Moopmsg (Stata)

<p align="justify">
Often times I find myself waiting on large Stata do files to run. In Python, I like to check the status of my code using a Telegram bot. It allows me to know imediately if a long running script has finsihed or hit an unexpected error. Stata does not easily have this fuctionality. </p>
<p align="justify">
I wrote this  program, moopmsg, for Stata. It is easily called in your do file. It can send any string message and small files to your Telegram. You will need to make a bot and supply the API token from Telegram. The help file provides details on setting up your bot.</p>

To download 
~~~
net install moopmsg, from("https://raw.githubusercontent.com/justin-mohr/moopmsg/main")
~~~

For more details on about moopmsg and its syntax
~~~
help moopmsg
~~~
<p align="justify">
I have found it quite helpful and hope you will as well! Please email me if you encounter any issues: mohr6@illinois.edu </p>



