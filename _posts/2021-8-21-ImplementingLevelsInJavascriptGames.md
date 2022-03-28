---
layout: post
title: Implementing Levels in Javascript Games with async/await
---

So, I was working on a a simple javascript game this weekend and I've
implemented the core game mechanics, initial world generation, and user
interface to display the score, instructions, etc. I'm feeling pretty good
about it, but then I had the daunting task of building levels. This was seeming
like it would be the most time consuming part of the whole ordeal and it was
honestly starting to seem like a pain.

Most tutorials for building your first HTML/Javascript game start out by
showing you how render objects on the screen, bind event handlers to those
objects so that you can move them around, and origanize your logic into
functions and/or classes. While this serves the function of showing developers
how to implement many basic features for their game, it misses out on a core
element of games: progression through levels.


