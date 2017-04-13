---
layout: post
title: "2017 Keynote - Ryan Newton - Haskell Taketh Away: Limiting Side Effects for Parallel programming"
excerpt_separator: <!--more-->

tags:
  - announcements
  
categories:
  - announcements
---
<style>
    img[alt=Photo] { 
        display: block;
        margin: auto;
        padding:10px;
        background: #f1f1f1;
        border:5px #f1f1f1 solid;
    }
</style>

We are announcing the last of this year's three keynotes, all speaking on the theme:

<p style="text-indent: 50px;"><b>What can C++ learn from other languages?</b></p>

Ryan Newton, member of the Glasgow Haskell Compiler steering committee, will explain how Haskell limits user capabilities and why that is empowering.

In designing parallel programming abstractions, taking away user capabilities is as important as granting them.  In his talk, he will explain the role of this idea in several different parallel programming libraries for Haskell, C++, and other languages--spanning from shared memory to big data.

![Photo](/images/speakers/RyanNewton.jpeg "Ryan Newton</i>")

<!--more-->

The Haskell language is an experiment in making purely functional programming practical, and, as such, much of its design stems from limiting where and how the user can employ side effects.  Haskell is almost 30 years old, but is used more widely, and is changing more rapidly, now than every before.  It's an exciting time for programming languages that use advanced type systems to accomplish formal software verification, and Haskell sits in midst of this revolution: at a juncture where it draws from the latest ideas in theorem proving languages, while at the same time remaining a practical programming language.

By clearing the canvas of unconstrained effects, Haskell and similar languages allow experimenting with specific combinations of effects that work well together: e.g. for transactional memory, for deterministic parallelism, or for accessing remote data sources.  In Haskell, we enforce these restrictions at compile time, via the type system.  While C++ cannot limit method's side effects directly through types, it is well suited to host embedded domain specific languages (EDSLs) that can incorporate the same ideas.

*Ryan leads a group of programming languages researchers interested in increasing the safety and parallel performance of high-level, declarative programs.  Recent work emphasizes extending the scope, practicality, and rigor of deterministic parallel programming.*

Our previously announced keynote speakers include <a href="/2017-conference/announcements/2017/04/09/d-keynote.html">Ali Çehreli, presenting  <i>Competitive Advantage with D</i></a>, and <a href="/2017-conference/announcements/2017/03/15/rust-keynote.html">Nicholas Matsakis, presenting <i>Rust: Hack Without Fear</i></a>.

<hr />

<b>Come join us in Aspen for C++Now 2017:</b>

- <b>[Registration is still open](https://cppnow2017.eventbrite.com) and</b>

-- Bryce Adelstein Lelbach, C++Now Program Chair

