---
layout: essay
type: essay 
title: Looking at Design Patterns
date: 2017-12-05 
labels: 
  - learning experience  
  - design patterns
  - web development
  - meteor
---
## Prolouge
Before you read through my essay, I would suggest to click on this link [here](https://sourcemaking.com/design_patterns).
This is only reccommended if you are not familiar with design patterns, as it may help you understand the terms mean, the link can also possibly help you visually see what I am talking about as well. 

## Essay portion
Originally I thought design patterns were particular methods that people can use to help smoothen the process of building 
projects. These sort of methods can help speed up your process on building software, or possibly make it easier to manage 
your apps. However, I thought it would focus more on the designing process rather than the actual code itself.

However, design patterns are not that. Instead design patterns are methods that professionals have thought up of, to help 
with common problems when building software, and more specifically it is dealing with code itself. These methods were thought 
up from trial and error methods from professionals, so that way it can speed up the learning and building process of newcomers.
I also learned that there are many design patterns out there, but just because something is a design pattern, doesn't mean it
is helpful. 

An example of such a pattern, is called "singleton". A singleton is basically adding a global variable, so you can use it 
throughout your code. However, this is not always a good thing, because good coding practices say that you shouldn't use global 
variables, and instead use classes and variables in that class. Another example is the practice where you don't touch code because
you don't know what it does, on a project that has been around for a while. Although, this may solve short-term problems, in 
long-term, that "old code that doesn't get touched" becomes irrelevant, and no one will know what it does. 

In my own experiences with my group project called "Campus Beats" for ics 314, we have used this meteor template called Bowfolios, 
and have tinkered and modified it to make an app that connects people through music. In this project, I have experienced "Observer"
and "Model-View-Controller" design patterns. 

Observer is when you deal with event handlers, and event handlers is when something is the subject 
and you apply these event handlers that keep track of it. If the subject changes, the event handlers need to know this, so it can change 
smoothly. In my group project, event handlers were used for almost everything, especially for filtering profiles on pages. There
was a lot of code, and it was actually pretty difficult to debug, especially when something went wrong.

Model-View-Controller is any website. There are three crucial elements to Model-View-Controller. 
- Controller: What decides what is shown to user, 
- Model : the database (hidden from user)
- View: What the user sees. 

The 3 all work together and is actually also another complex process. However, I feel that this design pattern is good for teams
because there are many things to do in this sort of design pattern. 

