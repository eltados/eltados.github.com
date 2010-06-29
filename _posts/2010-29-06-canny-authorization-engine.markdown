---
layout: post
title: [Shameless self promotion] Canny Authorization engine
image: http://sf-reaper.com/graphix/Parental/images/accessdenied.gif
---

I just profit of the first content blog, that no body is actually reading the blog to present one of the idea and the implementation of it.

[Canny](http://github.com/eltados/canny) is a java little library i wrote couple of month ago because i was annoyed of how the authorization logic was done it the application i'm working in my job and i wanted a side project.
I don't consider myself as an experience programmer and i'm working on a fairly old application that has evolved almost 10 years.
You can imagine that the authorization logic ( the application is very customisable ) can be rather complex and sprayed across all the application, view controller etc..

Canny was really a prove of concept and i want it to have 3 simples characteristics :

- a centralized place for authorization logic then reused everywhere ( view , web services , controller )
- very simple and flexible architecture that could be used anywhere
- implement a sorta [DSL](http://www.infoq.com/presentations/DSL-What-Why-How-Ola-Bini) in java ( i like DSL and like twisting the language and see some of the hidden or obscure feature)

This library has been influence by ruby, the programming language i like to use to hack thing around, and especially the [Cancan](http://github.com/ryanb/cancan) library for Rails


