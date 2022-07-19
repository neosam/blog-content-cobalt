---
title: Light and dark mode with some redesign
tags:
  - blog
  - redesign
published_date: "2022-07-19 19:59:23 +0200"
layout: default.liquid
is_draft: false
---
After some redesign I was wondering how hard it would be to support
light and dark mode.  Personally, I really like it when apps and
websites support it.  While light mode is blinding me at night, dark
mode makes it harder to read the content on bright surroundings. So my
point is:  It makes sense to support it.

But first lets talk about the redesign.  The design still is very cheap
since I'm a software developer and not a designer but it's at least
better than before.  A smaller title bar only displays the
name of the blog now and the page title will be displayed in
the main area along with the rest of the article where it belongs.

On the landing page, there is just the first paragraph of each post instead
of flooding it with the all the content which is available on the page.
So now each post takes about the same amount of space and if the first
paragraph is somehow interesting, the user can click it.

Then I've thought, the dark website looks somehow like a nerd who
lacks design skills made it.  Why not make a light version of it which
looks like a nerd who lacks design skills made it.  So, quickly used
the search engine of my choice ([DuckDuckGo](https://duckduckgo.com))
and I discovered the media query `prefers-color-scheme`.  More
information is at [CSS Tricks](https://css-tricks.com/dark-modes-with-css/).

All I needed to do is to move all the color definitions into the media
query and then it simply worked.



