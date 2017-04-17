---
layout: post
title:  "A customer writes in saying their “site won’t build”.  Compose your best short (2-paragraph) customer-facing answer without any additional data, that could be useful in the generic case but would also lead to a customer providing a more actionable response."
date:   2017-04-17 01:26:17
categories: site build
---

I would ask the customer to provide a log of their build attempt. This generally involves them clicking the button that says "Copy to clipboard" and pasting that up into either an e-mail or a pastebin. I'd examine the log to see if anything looked out of the ordinary for a working build.

Then, I'd ask the customer to provide some additional specifics as to what they meant by "site won't build". By clarifying the problem further, I might determine that they might have missing or incorrectly written configuration files or dependencies or might have inadvertently forgotten a "git push" after all the commits.
