---
layout: essay
type: essay
title: "Quick meteor templates"
# All dates must be YYYY-MM-DD format!
date: 2024-02-21
published: true
labels:
  - Engineering
---

## Using Meteor

I've used meteor for quite some time now, and now that I've spent dozens of hours using a meteor template for building web applications, and while I will definitely be super lost using other React frameworks, I have learned quite a lot about this specific way to design websites. I'd even say I'm quite comfortable with it.

To answer the question "What are design patterns?", I would start with the meteor starter template as an example.

The Meteor starter template has a basic example of many of the things that people would need from a full stack web application. From how users ask for specific pieces of information, to how the website accesses the information and displays it in an organized way, the Meteor "way" is a very typical pattern in building full stack web applications.

Design patterns range from factors such as the literal UI/UX design of the website, to the way that the web application can deliver data or take data from users. The many different ways that this data can be manipulated by the website are practically endless, but there are a few patterns that are quite literally the fundamental building blocks for nearly everything.


## Databases

An important thing I've learned from my use of the Meteor framework is using a backend, which is something I have not done up until this point. There are many ways to access a backend, but the formula is quite simple (at least in this framework I'm using). A database query is placed into an object, which can have endless objects inside. All of these objects have properties that contain some set of data.

Learning how to access this data was something that we learned all the way from the beginning of the semester, with the use of underscores to sort out and manipulate specific pieces of data out of a larger one.

That idea is basically the essence of web apps: you have a huge set of data, and users only need a certain piece of that data. 

The rest of the details in between... well that's the whole point of the class.

Of course, there are good ways and bad ways to do this data manipulation, and that's where good design patterns come in. Fortunately, we don't have to completely redesign database structures from scratch when we want to make our own custom software. The Meteor template is a crucial example of how to do basic web application functionalities. 

In short, I know that there are so many different ways to build a web app. I don't have to use Meteor, and I don't even have to use React. However, the Meteor framework takes the heavy lifting out of the hardest (and most crucial) design patterns, which I've had plenty of fun messing with in the past two weeks building a custom web app.