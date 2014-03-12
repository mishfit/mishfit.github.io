---
layout: post
title: "Protect Against Replayed Ajax Posts (in C#)"
date: 2014-01-05 04:13:56
categories: rest csrf replay-attacks
---

There's been plenty of talk about security theses days. Everyone has heard stories of compromised sites or payment systems (web enabled or not). While Microsoft wasn't the earliest adopter in the past, they've made it stupid-simple for developers to prevent malicious activities. You do, however, have to follow a rather strict pattern:

AntiForgeryToken
================
