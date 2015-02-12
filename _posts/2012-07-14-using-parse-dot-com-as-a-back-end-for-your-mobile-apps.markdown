---
layout: post
title: "Using Parse.com as a Back End for your Mobile Apps"
date: 2012-07-14 18:29
categories: iOs, architecture, services, model
---
[Parse](http://parse.com) has been growing in popularity and [mind share](http://www.businessinsider.com/meet-the-most-important-startup-of-2012-2012-7). It's a quick way to get a mobile application with a networked back end up and running. It saves you time from creating a REST API for your application's back end, and a mobile developer can build an entire app in native code, including the data model

###Pros:
**Quick iteration times** - If you want a simple [CRUD](http://en.wikipedia.org/wiki/Create,_read,_update_and_delete) application that allows your users to authenticate via facebook, retrieve some information, and maybe leave a rating or a comment with a simple data model Parse is very useful.

**Native development** - A mobile developer can do everything from the client side as the network layer and data store interface are baked into the Parse SDK. No need to deal with server deployment, scaling, uptime, etc.

###Cons:
**Server-side logic** - Parse does not allow you to run logic on your server. This means a certain class of problems that aren't simple database access (product recommendations, user matchmaking) are much harder than they need to be.

**Scalability control** - I'm sure Parse.com employs some good scalability engineers and can run their own platform well, but that's a far cry from being able to handle a scalability issue on your team when time is critical.

**Lock in** - Since you're using the Parse SDK, if you ever wanted to have more flexibility and control by switching to your own back end, it will take a lot of work extracting the Parse SDK from your client. In essence it can result in a large amount of [technical debt](http://en.wikipedia.org/wiki/Technical_debt) you have to pay down.

###The Bottom Line
It's good for a mobile hacker to Parse in his or her toolkit. It lets you quickly build an app with a back end and does a lot of heavy lifting for you.

If you're trying to build a business for the long term and control over your scalability is significant concern, or you require significant server-side logic, you're better off with your own back end. You could still integrate with Parse for some of its [nifty features](http://blog.parse.com/2012/07/06/pushing-to-queries-in-ios/), but having your own server stack will give you control when you need it.

As with any technology decision, in the end it's largely dependent on your use case.
