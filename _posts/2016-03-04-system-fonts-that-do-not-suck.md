---
layout: post
title: "System Fonts That Do Not Suck"
date: 2016-03-04
excerpt: "Choosing fonts wisely."
categories:
  - How to Use Technology
tags:
  - typography
  - fonts
  - design
---

Fonts are an essential part of the web. They are responsible for making websites beautiful and accessible. Whether you are using your CMS’s default theme or a custom design, fonts will make your web presence unique.

Which font should you use though? There are thousands out there, both free and premium. From the brilliant [Google Fonts](https://www.google.com/fonts) to the elegant [Typekit](https://typekit.com). There should be a font that suits your taste and needs.

But even if you find one, nobody can guarantee that your readers will like it as well. It may be the perfect font for you, but people are different with different taste. And even if your taste matches, why would you make the choice for your readers? It is your website we are talking about, of course, but you really do not want to upset them. Trust me.

Kyle Dreger, from [Audacious Fox](http://audaciousfox.com), has a simple solution: use native system fonts.  It makes absolute sense. Let your audience’s computer decide which font they will see when they read your text.

I decided to implement Dreger’s idea into this journal. So, from now on, if you are coming from an Apple device (iOS or Mac) the [fantastic San Francisco font](/thoughts-on-el-capitan) will be used. If you are a Windows user, then you are reading this with Segoe UI. On Android you get Roboto and on Linux, well, you get whatever flavor of Linux you get.

<i class="fa fa-lightbulb-o"></i> Smashing Magazine provides a very <a href="https://www.smashingmagazine.com/2015/11/using-system-ui-fonts-practical-guide/#details-of-approach-b">comprehensive guide</a> on what is shown where and which are the different approaches to do it.

Here is what code Dreger uses which I adopted as it is:

<code>
body {
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Helvetica, sans-serif;
}
</code>

Fonts really make a difference.
