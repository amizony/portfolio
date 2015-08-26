---
layout: post
title: To-do List
feature-img: "img/tasklisthead.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/1686132/webflow_landingpage_1x.jpg"
short-description: A self destructive task list

---

# Description

A to-do list application where each task has an expiration time and should be completed before.

![To-do-list]({{ site.baseurl }}/img/tasklist01.png)
![To-do-list]({{ site.baseurl }}/img/tasklist02.png)


A live demo is available on Heroku: [To-do-list](http://my-little-task-list.herokuapp.com/).  
The source code is available on Github: [To-do-list](https://github.com/amizony/self-destructing-task-list).


# Context

For my second application, I wanted to do one of the classical application every developer should be able to do.
I opted for a to-do list because I was interested in the storing of the tasks for their persistence.  
I used Angularjs as base framework to improve my knowledge of it's architecture and to allow me to simply make a single page application.
I used then Firebase as Backend to store my tasks.


# Features

Over the simple ability to add tasks and mark them as complete, I added other:

* Tasks can be added with a priority
* Tasks expire if not completed within one week
* The History allow to see completed and expired tasks
* Tasks are persistent and stored on-line
* Each user has the possibility to have his own account
