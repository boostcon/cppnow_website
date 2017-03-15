---
layout: post
title: "2017 Keynote - Niko Matsakis - Rust: Hack without fear!"
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

At C++Now, we love to challenge the norm.
 
Many of our favorite C++Now keynotes have presented views that differ from accepted C++ philosophy and thoughtfully question the status quo in the C++ community. 

We have a few keynotes this year, and they share a common theme that reflects our desire for new perspectives:

<p style="text-indent: 50px;"><b>What can C++ learn from other languages?</b></p>

Naturally, we started with **[Rust](https://www.rust-lang.org)**.

**Nicholas Matsakis**, a senior researcher at Mozilla and a member of the Rust core team, will be giving a keynote at C++Now 2017 about ownership in Rust.

![Photo](/images/niko_matsakis.jpeg "Nicholas Matsakis, Mozilla, Rust core team")

<!--more-->

Through the concept of zero-cost abstractions, C++ has shown that it is possible to combine low-level control with high-level programming concepts. Rust is language that aims to offer the same sorts of zero-cost abstractions that C++ is capable of, while also enforcing memory safety and data-race freedom. The secret sauce is Rust's core notion of "ownership", which enables:

- Memory safety without garbage collection;
- Concurrency without data races,
- Abstraction without overhead.

In this talk, I'll explain ownership and show how Rust uses it to guarantee thread safety, amongst other things. I'll also talk about how Rust is designed to scale to large code-bases, sharing some of our experiences here at Mozilla from integrating Rust code into Firefox.

One final theme of the talk is that the benefits of ownership go beyond having fewer bugs: once you are freed from the need to prevent memory-safety violations, it becomes possible to write - and *maintain* - programs that aggressively pursue parallelization and other kinds of optimizations that would have been too risky or too difficult before.

*Nicholas Matsakis is a senior researcher at Mozilla research and a member of the Rust core team. He has been working on Rust for nearly six years and did much of the initial work on its type system and other core features. Prior to working on Rust, he did his undergraduate studies at MIT and completed a PhD at ETH Zurich in 2011. He also spent several years at DataPower Technology, a startup since acquired by IBM, working on the JIT compiler and networking runtime.*

<hr />

<b>Come join us in Aspen for C++Now 2017:</b>

- <b>[Registration is still open](https://cppnow2017.eventbrite.com) and</b>
- <b>[the student/volunteer program is still accepting applications!](/student_volunteer_application/)</b>

-- Bryce Adelstein Lelbach, C++Now Program Chair

