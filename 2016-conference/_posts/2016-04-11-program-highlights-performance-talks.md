---
layout: post
title: "2016 Program Highlights: Performance Talks"
excerpt_separator: <!--more-->

tags:
  - announcements
  
categories:
  - announcements
---

Performance and efficiency are always big themes at C++Now. This year is no 
exception - we have a number of talks about performance: 

- <b>Jason Turner</b> - <i><a href="http://sched.co/6Sg7">Practical Performance Practices</a></i>
- <b>David Stone</b> - <i><a href="http://sched.co/6SYt">Exceptional Performance</a></i>
- <b>Sebastian Redl</b> - <i><a href="http://sched.co/6Sfr">Diet for your Templates - Reducing Code Bloat in Your Templated Library</a></i>

We still have room for a few more people at this years' conference! 
We have <a href="https://cppnow2016.eventbrite.com">a couple registration slots left</a>, and our
<a href="https://aws.passkey.com/g/54941837">group rate at Aspen Meadows, the conference hotel,</a>
is still available. Come join us in Aspen this May!

Some more information about these performance talks: 

<!--more-->

<h4><b>Jason Turner</b> - <i><a href="http://sched.co/6Sg7">Practical Performance Practices</a></i></h4>
In the past 6 years ChaiScript's performance has been improved by nearly 100x.
This was not accomplished by adding a virtual machine or performing dynamic
recompilation. Instead, these increases have been accomplished by moving to
more simple, cleaner, idiomatic C++ and by following some simple rules. We will
outline these concepts with examples for how they both simplified code while
improving performance. 

<b>About the Speaker:</b> <i>Jason Turner is an independent contractor with 15
years of development experience. For the past 5 years he's been specializing in
cross platform development, scripting of C++ libraries, automated testing and
code quality analysis. Jason is the the co-creator and maintainer of the
embedded scripting language for C++, ChaiScript, and the author and curator of
the forkable coding standards document cppbestpractices.com.</i>

<br />

<h4><b>David Stone</b> - <i><a href="http://sched.co/6SYt">Exceptional Performance</a></i></h4>
When many of us choose C++, performance is one of the most important factors.
It is so ingrained in the culture of C++ that the single most important tenant
of C++ is probably "You don't pay for what you don't use". This shows up in
almost all components of modern C++: zero-cost abstractions backed by a
powerful optimizing compiler. Yet there is one component of the language that
appears to violate this rule: exceptions. The mere possibility of exceptions
can force the compiler to generate different, slower, code than it otherwise
would have. Throwing an exception is a slow operation, and exceptions can lead
to an increase in code size. There is a lot of conflicting advice on what
exactly the programmer can do to make sure that they only pay for what they use
that runs the gamut from "Don't worry about it" to "Pass this special flag to
your compiler to turn off exceptions". The situation is only made more
complicated by the introduction of the noexcept keyword. In this presentation,
we will discuss exactly what effect exceptions have on the performance of an
application, backed up by numbers from both benchmarks and real world
applications. We will go into the details of hardware architecture and memory
hierarchy to try to understand exactly why code performs the way it does. Could
it ever make sense to say that you using exceptions for performance reasons?

<b>About the Speaker:</b> <i>David Stone has spoken at C++Now and Meeting C++.
He is the author of the bounded::integer library and has a special interest in
compile-time code generation and error checking, as well as machine learning.
He works at Markit integrating real-time financial data. He has written an
algorithm that solved the traveling salesman problem in polynomial time. He can
square the circle and divide by zero. He can move his king into check. He once
wrote an optimizing compiler that solved the halting problem, but doesn't need
to use it because his code is already optimized.</i>

<br />

<h4><b>Sebastian Redl</b> - <i><a href="http://sched.co/6Sfr">Diet for your Templates - Reducing Code Bloat in Your Templated Library</a></i></h4>
We developed a heavily templated-driven library, IoC++, in-house at our
company. Using it, we discovered that it generated huge object files and
libraries, leading to very long link times, large executables, and even linker
crashes. In this session I present techniques we used to reduce the bloat in
the library and got our link times down to acceptable values. 

<b>About the Speaker:</b> <i>Sebastian holds a BSc in Software Engineering from
the Technical University of Vienna and is currently finishing an MSc. He is
working at a small software company called Symena (part of Teoco), and recently
spent a year's sabbatical working at Google. He has contributed heavily to the
Clang C++ compiler and maintains the Boost.PropertyTree library.</i>
