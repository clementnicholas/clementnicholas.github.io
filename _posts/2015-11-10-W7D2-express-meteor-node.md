---
layout: post
title: W7D2, Node, Express, and Meteor with some WebSockets
date: 2015-11-10 20:38:28 -08000
categories: jekyll update
---
Today, we covered some more Node.js and introduced some potential technologies to work with for our final projects. We also went over the use of Web Sockets and how they are kind of awesome in the way they work. 

Web Sockets are awesome because there's a continual connection between client and server, meaning we can send data instantaneously basically. This enables some pretty cool stuff when it comes to interaction between users. If a client is doing something to the server, it gets sent out to all the other clients accessing that server within the connection. This enables massively scalable realtime platforms. 

It also blows AJAX out of the water as far as realtime functionality. Since one connnection offers bi-directional communication, we don't have to wait for a bunch of different connections between client and server, or in AJAX's case, cross-browser realtime communication. Anyways, cool stuff for building fast, lightweight, interactive apps with multiple users sending and receiving content in realtime.

We also looked at express.js and meteor.js. We will start with express, a great, lightweight framework for node applications. The way you pass your requests and responses between server-client is really handy, especially considering you are running it off of one main JS file (app.js). Also, you have access to all of nodes handy modules. SWEET. 

Express supports ejs to help with renderings (also, a lot of templating engines are supported... +1) while the general app directory is not as bogged down as a rails file might be. Considering I find this much easier to navigate, I highly enjoy this aspect. Routing is fairly simple which makes for easy back-end navigation. All in all, definitely considering using node and express for the final project.

Also, METEOR. It looks tight. It templates on both the client side and server side... WHAT! It almost feels like cheating because you write so much less code. This is because it's very reactive and just finds things you need and requires them without you having to specify much. It only supports MongoDB as a database but that's not much of a barrier. 

Meteor's relatively new so usage isn't as high as you'd expect, but I think it's worth investigating as it's about as easy as it gets as far as building an application. Oh, and also deploying is simple. And so is making your web app mobile-friendly. 

Anyways, that's all for today. Tomorrow, I'll have my final project group and idea hopefully so stay tuned.