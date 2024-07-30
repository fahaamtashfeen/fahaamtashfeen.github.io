---
layout: post
title: 7 Hours Later
author: Fahaam
category: Zenith
---

I've been working on google authentication for login on Zenith Gallery. Problem is, I made the code a lot more modular (took code from the express server and seperated it into a bunch of files). This is good practice for scalability, and sometimes readability.

But for myself there was the added dreadful debugging. Which took 6.5 hours longer than I expected. After all, it's the same code but just in different files right?

Wrong. The code does need to be slightly adjusted. It was a good learning experience. That was the first hour.

The rest of the time was spent debugging the gmail login which was already working prior to the changes I made. I'm not even sure that length of time feels worth it right now because the true error resided in a **single word**.

That word wasn't caught by myself.
Nor chatGPT.
Nor Claude.
Nor Gemini.

Eventually it was a combination of myself and ChatGPT finally figuring it out.

I've since spent more time since working on authentication. So after logging in, the web app needs to keep track of the fact that this user IS infact logged in, rather than just logging in through gmail for no reason. This tracking was very difficult to debug and it actually ended up having to do with my front-end and back-end setup which I posted about earlier (and said it was working ***el oh el***).

All good learning though. Also reminded me why I cant stand the current state of web dev. But we will push through and maybe my opinion will change. I'm open minded. I don't want to dislike web dev. A topic for another time perhaps.

I didn't edit this so if you see any typos lmk.

Bye,
Fahaam