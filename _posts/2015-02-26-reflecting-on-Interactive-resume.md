---
layout: post
title: Reflecting on P2 - Interactive Resume
---

Just taking the chance to add my concept deliberations on P2 submission
which covers JavaScript Basics.

###What can JavaScript do that HTML/CSS can't?

HTML is a markup language which defines the content and structure of web
pages.  CSS is used for the styling of those pages.  Both of these are static
in their nature.  JavaScript, which is a client-side programming language
(meaning scripts are read, interpreted and run in the client) adds dynamic
elements to web pages such as automation, animation and interactivity.

JavaScript can do many things which cannot be done via HTML/CSS alone.  By
accessing information from the browser and the web page it runs in it can
change any HTML/CSS adding custom prompts/alerts and can also add/update/
remove content on the fly, responding to events such as mouse clicks or
keyboard entries, pages loading or timeouts.

### Function Use - What is the advantage of functions over 'spaghetti code'?

Functions in JavaScript are used to bundle instructions together into sections
which can then be called at a later time (even multiple times) without needing
to rewrite all the code again.

As there is a single place where the instructions occur rather than multiple
repetitions of the same code, changes to that single block will then apply to
each place where the function is called.

Also, by grouping the code up into functions you can easily follow which code
will run when particular actions are taken.

### APIs - What is an API?  Why is it important?

An API is a set of instructions and standards for accessing an application
which abstracts the underlying code complexity and allows you to easily
leverage the code within an application to represent within your own, for
example by querying Google Maps API you can ask it to give you a section of
the map or to plot a set of points on a map without having to know anything
about writing code to develop a map application of your own.

In short APIs let you write apps that use other apps, taking input from your
app and returning output back to your app after applying it's own logic.

This is important because means that you don't have to spend time & resources
to develop your own code (especially if you don't have the relevant skills)
when others have done it for you.  It also allows you to reuse the data from
existing applications and create new experiences which the original developers
may not thought of.

There are many examples of APIs from single applications like Facebook and
Twitter to aggregated APIs like IFTTT which in turn leverages APIs from many
web services.  Interestingly Udacity even has its own APIs for accessing all
of its course information.  I will be using the Google Maps API in my online
resume.  At work my team deploys APIs in its chat platform to allow other
teams to present chat data in other applications such as internal help desk
systems.

