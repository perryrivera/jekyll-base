---
layout: post
title:  "Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users"
date:   2017-04-17 01:19:43
categories: DNS configuration
---

One challenge for less-technical internet end-users is they tend to use their apex domain as their canonical name, instead of starting their domain with the prefix "www". It is highly preferable to do the latter to ensure resiliency during outages and DDoS attacks and also save extra DNS lookups at the user level.

Another challenge is that end-users will need to configure their DNS provider's page to point to Netlify. The providers typically have some web or GUI configuration tool to modify this information and generally involves adding a CNAME record to the zone file.
