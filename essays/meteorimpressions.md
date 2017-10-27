---
layout: essay
type: essay
published: true
title: Meteors and Asteroids
date: 2017-10-26
labels:
  - Meteor
  - Application
  - Client/Server
---

## Exosphere
When you first come across it, the name sticks out as a fast javascript framework, and that's essentially what it is. Meteor is designed to simplify the relationship between the client and server side. I learned this javascript framework in my class as an introduction to asynchronous programming. First starting out, there was a clear learning curve. Previously, we learned the basics of the javascript language in its raw form, then we went on to underscore which was just a library you can utilize to make simpler the modification of data. Naturally, we went on to HTMl and CSS and Semantic UI which we can use to, again, make our lives easier when designing web pages. All of that was as a prerequisite to delve into the development of the back-end and putting it all together to make an interactive web page. What better way to learn a framework than to develop a project. The project in question was called "digits". 

## Mesosphere 
Completed in 6 parts, we were tasked with making a fully functional application that allows the user to simply add contacts to their contact list. The first most confusing thing about learning any language is the syntax. I was confused at how little actual javascript I was looking at. I came to program but left realizing that the framework was supposed to minimize the writing of any logic. Most of the logic was based on event handling and database manipulation. Again, the syntax was dissimilar to javascript as it had its own smarter way of creating event handlers. 
<br />
Another concept I was dumbfounded by: code inside the HTML. Meteor uses Spacebars, which is similar to Handlebars (I don't know what any of these terms mean) to embed logic inside the HTML to display elements. At first I thought that was messy. Shouldn't we be separating the markup from the code? But it works together really well with the use of Spacebars templating.
<br />
Here's a major thing about meteor application development: you have to import everything! Literally, everything. Almost each directory will require an index.js file that imports the files already in that directory. Forgetting to import a file will most likely result in a broken keyboard or two. The thing is, it's just one tiny little line of code, so do NOT forget your imports.

## Troposphere (Ground)
Here's the only horribly ugly thing about meteor - version handling. If there's anything wrong with your version of meteor and your project's version of meteor, there are some bugs bound to be lurking. 
<br />
On a side note that might not be directly related to this, I had to run a ```meteor npm run install```. My computer is not a bad computer by any means but it took me more than 10 minutes to install before I took to google to find the reason why it wasn't installing. It wasn't until the next day where I just let my computer keep running that it FINALLY installed after a good 30 minutes. Rant over.
<br />
Overall, meteor is an awesome framework, but be wary, it might all come crashing down on you. 

