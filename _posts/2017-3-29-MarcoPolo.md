---
layout: post
title: The Marco Polo Project
feature-img: "img/sample_feature_img.png"
---

## Situation   
Our worlds revolve around our devices. We carry them around religioulsy since they allow us to live  our lives the way we like them. They almost make us Cyborg.  They connect us to our realities and they are connected to ours. Some people have a harder time than others in staying within a reality. They forget to check in with a quick text. They forget to call. They are too distracted to respond to an email.  I happen to be related to one of those.  I didn't want to harrass him but I also didn't want to worry.  
I had to find another way.

## Action
I wanted to know when devices became active on  the router since it's the hub of all digital comings and goings of the house.  
The hardest part was figuring out a course of action when I had little notion of what that entailed. Much research was done. I looked for similar projects and with help from my mentor, learned about the technologies that I could use.  There are some very generous people out there who have taken the time to create well explained tutorials. They will forever be one of  the reason I love the internet.  
### Capybara  
No, not the cute and ridiculously large  [rodent](https://img.buzzfeed.com/buzzfeed-static/static/enhanced/webdr05/2013/4/29/14/enhanced-buzz-5639-1367258753-0.jpg?downsize=715:*&output-format=auto&output-quality=auto).  
"Capybara helps you test web applications by simulating how a real user would interact with your app. "  
and Capybara will also just pretend to be human and navigate a webpage for you without much fuss: write this here, click on that- sure, no capybara problem :)  
So Capybara went and collected all the information I needed and then Ruby saved it as json files for me.   
### IFTTT
I needed a way to be notified of the changes to the devices on my router. Again my mentor pointed me in the right direction: IFTTT.com.   
There is so much potential with what they offer, it's hard not to get distracted.
The catch is that there isn't much documentation. It was hard to figure out where the different parts were. (Detailed instruction are on the Project's github page) 
###cron
Now I want to make a crontab for everything!   
I had to wrap my Ruby code in bash to get it to run. 
### RaspberryPi
That was also daunting. A whole new operating system to deal with: Raspian (even if it's really just Linux undercover). Having to talk to it through the terminal was exciting. Such a tiny computer that could host my project and keep it running. Downloading the binaries was tricky. Phantomjs was the toughest. Finally found Phantomjs "unofficial binaries for raspberry pi" and all was ok.

## Result
Now I always know when my son is home. In fact, I get emails day and night letting me know within 5 minutes of any change to the devices on the router. Some devices such as the iphones tend to pop on and off the network based on how strong the signal is. I get alot of messages from those. For the most part it works well.  I know if a computer has been booted up and if a new cell phone has joined the network. My daughter says I'm a stalker.
## Interestingly
I learned alot about integrating technologies. I tried to keep it as simple as I could and as small as possible.  
One of the laptops likes to wake up in the middle of the night!  

the [project ]( https://github.com/RobotMermaid/MarcoPolo) 