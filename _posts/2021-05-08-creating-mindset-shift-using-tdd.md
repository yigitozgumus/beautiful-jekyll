---
layout: post
title: Creating Mindset Shift Using Test-Driven Development
subtitle: Can TDD change the way you think about programming ?
cover-img: "../assets/images/posts/tdd/post_header.jpg" 
tags: [blog, programming, test-driven-development, tdd]
comments: true
---

I recently finished reading Test-Driven Development by Kent Beck. 
The book explains the TDD concepts literally by doing TDD style 
development iterations on 2 different code samples and further 
explains the design patterns, concepts around the topic.

For those who don't know, test-driven development is a paradigm that 
suggests writing the related test before writing the actual code. 
The iteration cycle of test-driven development consists of three 
phases: red, green, and refactor.

![](../assets/images/posts/tdd/tdd-cycle.png)

Let's simulate the typical development cycle using TDD. First, you write the test 
for the functionality you want to implement. Then you write the minimal amount 
of code to make that test green. This transition from red to green state facilitates maybe a somewhat odd thing for a software engineer because you write literally the 
minimal amount of code for the test to pass. That might mean simply returning the result you want or create the object without doing any prior computation. To me, that part of 
the cycle seemed cumbersome at first. Refactoring state is where the TDD shines and 
enables developers to write more concise and clean code. You refactor the code to pass 
the test appropriately. If the chunk of the feature you want to implement is small, then 
congratulations, you developed a feature with its corresponding test. In reality that is 
usually the small percent of the task done.

The above process represents one of many iterations of a TDD session but the main 
thinking that creates this small many iterations made me realize how it can change 
the way you think about a solution.

These questions excerpted from the book really visualize the process of writing 
tests and dividing the current tasks into approachable chunks from top to bottom:

- Where should you start building a system? With stories, you want to be able to tell about the ﬁnished system.
- Where should you start writing a bit of functionality? With the tests, you want to pass with the ﬁnished code.
- Where should you start writing a test? With the assets that will pass when it is done.

For bigger tasks and feature implementations, I think TDD facilitates as a sort of 
framework for thinking the problem and analyzing what needs to be done according to what. 
For that reason, using the TDD approach at my work and experimenting with it on my 
personal projects highly intrigued me. Rather than focusing on the implementation details 
and analysis constraints, planning the implementation by dissecting the target behavior 
and its potential responses is a more natural way of thinking to develop an 
implementation.

Come to think of it, throughout my programming life, both academic and 
professional, I wrote tests to check the correctness of the implementation 
but I never designed the solution using the test-first approach. While reading 
this book, I tried and applied the mentioned thinking style to the project I 
currently work on at work (which is an Android application with approximately 
200K lines of code) and I find that not only the solution may be designed with 
more clear constraints using TDD, but also it helps to think in a way that is 
more coherent with the app's architecture.

I think thinking tests to create the implementation path is a different type 
of mental exercise for a developer. It is questionable whether it triumphs the 
classic approach, but certainly is a highly effective skill for a software engineer 
to have. I highly recommend reading the book and testing the TDD approach for 
writing code. I will be experimenting with TDD in the future and plan to write 
another post about its pros and cons.

Until the next post,  
Yigit

[^1]: [Goodreads Link](https://www.goodreads.com/book/show/387190.Test_Driven_Development)



