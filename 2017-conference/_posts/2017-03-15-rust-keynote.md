---
layout: post
title: "2017 Keynote - Niko Matsakis - Rust: Hack without fear!"
excerpt_separator: <!--more-->

tags:
  - announcements
  
categories:
  - announcements
---

At C++Now, we love to challenge the norm.
 
Many of our favorite C++Now keynotes have been the ones that presented views that differ from accepted C++ philosophy and thoughtfully question the status quo in the C++ community. 

This year's keynote theme reflects that desire for new perspectives: **"What can C++ learn from other languages?"**

Naturally, we started with **Rust**.

![Niko Matsakis](/images/niko_matsakis.jpeg)

**Nicholas Matsakis**, a senior researcher at Mozilla and a member of the Rust core team, will be given a keynote about ownership in Rust and how it enables memory safety without garbage collection, concurrency without data races and abstraction without overhead.

<!--more-->

Through the concept of zero-cost abstractions, C++ has shown that it is possible to combine low-level control with high-level programming concepts. Rust is language that aims to offer the same sorts of zero-cost abstractions that C++ is capable of, while also enforcing memory safety and data-race freedom. The secret sauce is Rust's core notion
of "ownership", which enables:

- Memory safety without garbage collection;
- Concurrency without data races,
- Abstraction without overhead.

In this talk, I'll explain ownership and show how Rust uses it to guarantee thread safety, amongst other things. I'll also talk about how Rust is designed to scale to large code-bases, sharing some of our experiences here at Mozilla from integrating Rust code into Firefox.

One final theme of the talk is that the benefits of ownership go beyond having fewer bugs: once you are freed from the need to prevent memory-safety violations, it becomes possible to write - and *maintain* - programs that aggressively pursue parallelization and other kinds of optimizations that would have been too risky or too difficult before.

*Nicholas Matsakis is a senior researcher at Mozilla research and a member of the Rust core team. He has been working on Rust for nearly six years and did much of the initial work on its type system and other core features. Prior to working on Rust, he did his undergraduate studies at MIT and completed a PhD at ETH Zurich in 2011. He also spent several years at DataPower Technology, a startup since acquired by IBM, working on the JIT compiler and networking runtime.*

