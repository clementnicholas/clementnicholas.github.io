---
layout: post
title:  "First Post: The Beginning of The End @ Lighthouse"
date:   2015-11-09 20:41:28 -0800
categories: jekyll update
---

Hi. Welcome. How are you?

I don't know how you found your way here but I'm glad you did. My name's Nick and I'm in the web development bootcamp at Lighthouse Labs in Vancouver. In retrospect, I wish I had started this blog at the beginning of the bootcamp, but then again, I would have had no idea what I was doing. Today is the first day of week 7. It's an 8 week program. We've moved into advanced topics, and every day I hope to use this blog to recap some of the things we covered and some questions I might have. Maybe I'll provide some cool links even. We will see. 

Here's a quick recap of where we've been in weeks 1-6. We started working with the Ruby language and object-oriented programming concepts, moved into SQL and Active Record in Week 3, and built our own web applications for our midterms using Ruby/Sinatra with however much front-end we wanted to throw in there. If you look around, you can probably find some info about what my group built. Week 5 we covered the Model-View-Controller architecture and Rails by building an application using that framework. What a BEAST it is! Week 6 was all front-end, focused on Javascript, JQuery, and Ajax. So we've covered a lot of ground (by no means is this comprehensive, just highlights).

Which brings me to today. NODE! I've personally been excited to start working with Node.js for a few reasons.   

  1. At the end of the day, I love javascript.  
  2. It's a super hot way to develop server-side applications.  
  3. I hear it's got some bomb frameworks.  
  4. JAVASCRIPT.  

We primarily worked with [learnyounode][learn-you-node] today, an open source npm module that teaches the basics of how to use node. It's pretty good providing insight into synchronous & asynchronous I/O, filesystem operations, TCP and HTTP networking, events and streams. And it runs on the command line.

Here are some of my biggest takeaways.   

--- Node has some AWESOME core-modules. And some pretty badass exports to go along with them. The core functionality built in was very easy to use and understand. Probably because [the docs][node-docs] are really good. Or at least I found them to be.   

--- There is no global context in Node, so the current scope doesn't get polluted. This is still a bit fuzzy for me, but it seems like it would be more light-weight and secure. Variables can't be accessed globally. Huzzah!   

--- The fact that files and modules are in one-to-one correspondence is pretty sweet. And to pass exports on you can just define what you want to pass on as an export and then require the module in your file. Pretty tight I think. At least it makes sense.  

--- It's pretty intuitive as to what modules it loads. Also, starting a server and making http requests is fairly straightforward, as are streams. But callbacks man. These are scary. Which brings me to my final point.  

--- CALLBACK HELL IS REAL! I did some more reading and found this post to be pretty solid. But anyways, yea, [callback hell][callback-hell] seems like something I don't want to deal with. Ever.   

Anyways, thanks for the time and stay posted. We will see how well I do with this but hope you've found it at least slightly entertaining. 

Until tomorrow, Cheers.  
-Nick

[node-docs]: https://nodejs.org/api/
[callback-hell]: http://callbackhell.com/
[learn-you-node]: https://github.com/workshopper/learnyounode/