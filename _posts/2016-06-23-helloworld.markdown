---
title: "Hello world: I have a purpose"
layout: post
date: 2016-06-23 15:00
tag:
- software engineering
- context
- design
blog: true
---

# Hello world: I have a purpose.

## Every line of code you write fulfills a dream.

**_Hello world_** is maybe one of the most common lines of code written ever (_disclaimer: this is just a random guess, do not take my word for it :)_). Displaying this text in a program is the most basic action one can do in any programming language.

> A Hello world program is a computer program that outputs or displays “Hello world” to the user.
[source](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program)

What is more interesting about this program is that represents an important aspect of software development: it has a purpose, it was created to interact with a user and display a greeting.
If we think about it, the same holds true for most of the lines of code that have been written: they all end-up as part of a product that will perform an action that is useful for something. Well! to be fair, maybe the lines of code that I wrote while perfecting my first C _Hello world_ program do not count ;)

You might wonder, why is this important? in my first post {% post_url 2016-05-02-curiosity %} I mention that is important for a software developer to have contextual information about where the software is used. This contextual knowledge can trigger new ideas that can provide value to the user and fulfill a goal.

This might not be a surprise for us, software developers, in the end we all know that somebody will be using the software we write and this will be used for something, right?
We also know that our software will be shipped in a product, and we know that it will solve a problem with enough value that revenue will be made from it. But, is it this true? Are we aware as software developers of the context where our beautifully crafted lines of code are immersed? if so, do we know to details? Such as the business implications of this product, should we even worry about that?

My opinion on this is that we should care, if we want to move from engineering mindset to a more design mindset. It is more obvious for instance that a front-end developer is more aware of the user interactions happening in the web page. The same applies for app developers, who are more immersed in details of user interaction. But, what about web backend developers, or firmware developers, or other software developers whose lines of code are not directly visible to the user but they are created to run in a specific context.

Take for example an embedded software developer who is writing safety critical software for a unmanned vehicle. In this case, some components of the software can be written without knowing the context where the software will be used. This is possible because there are strict regulations that require system designers to specify requirements, and each module during the design phase. Therefore, a software developer can take these requirements and write code that fulfills them. However, if the software developer wants to move more into designing the modules, a deeper knowledge of contextual information can help the designer to specify more accurately the modules.

Let me give you an example for this is: let’s say you are designing a new product that will help a user to find its way home with less than 10 dollars. There are multiple possibilities to accomplish this task. You could use another person to do this job. If you are lost, you call home and mom will pick you up. Or you can call a cab and it will do the same job, as long as you know where you live. Both options probably cost more than ten dollars. But if you know more about the context, you might have a case where only people will use the product whose age is above 20 years old and who have a car. Then what you might need is a device that can guide you home. The possibilities are endless and the more you know about the context the easier will be for you to find the most suitable solution.

Nowadays a smart phone application can be written by a 12 year old, because the tools to write software have progressed to much that is intuitive for a child to write the software. As a result, nowadays is becoming more important the knowledge you have about the situation, rather than your programming skills. The more information you have, the better solutions you can give to a problem. Of course the programming skills you have are still very important. A 12-year-old child might not be able to write software for safety critical operations or high performance 3D graphics rendering. But in the end, it is still true that the more you know about the context the better designs you can make.

So, what do we do now? I have spent most of my life learning new programming languages, mastering software design principles, and learning about the latest trends in programming frameworks. All this knowledge is not going to the drain, but it is not enough to develop successful product. You need to be able to incorporate contextual knowledge into the design process of a product.

Luckyly Software Engineering defines a set or principles and practices that a software designer should follow in order to design software that meets its requirements. The software needs to do what is supposed to do and it should do it right. Otherwise, the product will fall short in one or many aspect of its operation, the picture below explains it better than me:

![Product design]({{ site.url }}/assets/images/product_dev.jpg)
[source](http://bob.yexley.net/the-software-development-conundrum-estimation/)

Here is where we can strengthen the process, what we need to do is follow a more formal design process where software development is not the last part of a product development. Software development should be involved since the early stages of product design. The earlier we can plug our knowledge into the design process, the more possibilities we have to develop successful products. In the end, it is us developers who push the boundaries of what is possible, of course with the collaboration of all the team.

However, all this sounds easier than done and this is where I will stop this post. In my next post I will dive further into the process of designing a software based product. I will explore the different stages of product development and where can we plug ourselves to get the most out of our software engineering knowledge. This is also a good moment to stop because I would like to know what do you think about all this rambling of me. If you are a software developer who thinks this is non-sense, I would like to hear from you. Leave your comments in this post or write me an email at omar.ejv@gmail.com

But, before you leave, if you are a fellow developer, let me make your day just a little more fun. Enjoy! https://www.gnu.org/fun/jokes/helloworld.html


