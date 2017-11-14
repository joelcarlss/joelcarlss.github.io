---
layout: post
comments: true
title:  "Robots & Humans"
date:   2017-11-12 13:34:00 +0100
categories: Exam 1
---

##What is robots.txt & humans.txt

### Robots.txt
“Web robots” wander the web all the time, collecting data. These robots can for example collect data for search engines like Google where the data that gets collected is data we can use to search the web for what we want to find. But other robots might have different intentions. Robots can collect email addresses that will be used for spam emails. The bad robots are hard to control. They’ll collect all the data they can find. But the good robots are controllable thanks to our robots.txt file. 
When this type of robot checks put your page, the first thing it will do is to look for a file at “URL”/robots.txt and follow the instructions. The instructions can be like this. 
```
User-agent: *	(Tells that rules apply for all robots)
Disallow: /		(Tells that no data should be collected)
Disallow: /tmp/	(Tells the robot not to touch the directory /tmp)
Disallow: /dir/contact.html (Tells the robon not to touch a certain page)
 ```

I used the following restrictions:
``` 
User-agent: *
Disallow: /	
 ```

For this page right now, there is no point for indexing. The only one that needs know of my page in this phase is my teachers which have the link. 

### Humans.txt
Every website got an author. Probably more than one. But most websites isn’t built to show of developer skills any more. They have other purposes like a webshop or a newspaper and the author's written in a newspaper is those who wrote the news. At a company site or a webshop the names written in the website will be the CEO or seller to contact and the creator is the creator of the company. Therefore we can use a file at “URL”/humans.txt where we can add all the information we want about the developers behind the site. 

I’ve written the following in my humans.txt file:

``` 
Developer: Joel Carlsson  
Contact: jc222mw [at] student.lnu.se  
Twitter: @joelcarlss  
From: Vaxjo, Sweden
 ```


Sources: 

* [robotstxt.org](http://www.robotstxt.org/)  
* [humanstxt.org](http://humanstxt.org/)
