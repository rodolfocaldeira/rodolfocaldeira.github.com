---
layout: post
title: Responsive Design Kit
excerpt: Everything that you need for your next responsive project.
---

If you're planning in developing a responsive project the following articles will get you up to speed with everything you need to know.


- Chris Coyier, [Notes to an Agency Starting Their First Responsive Web Project](http://css-tricks.com/notes-agency-starting-their-first-responsive-web-project/)
- Ethan Marcotte, [Answers your responsive web design questions](http://www.netmagazine.com/interviews/ethan-marcotte-answers-your-responsive-web-design-questions)
- Metal Toad has [A Simple Device Diagram for Responsive Design Planning](http://www.metaltoad.com/blog/simple-device-diagram-responsive-design-planning)
- [MediaQueri.es](http://mediaqueri.es/) get yourself inspired

Although I agree with Ethan Marcotte in regards to how the different breakpoints should be added to your project, sometimes you just need to target specific devices.

- Chris Coyier as got your back with [Media queries for standard devices](http://css-tricks.com/snippets/css/media-queries-for-standard-devices/)

While the W3c Group is working hard to figure out responsive images the following approaches will take you a long way.

- [Picture Fill](https://github.com/scottjehl/picturefill),
- [RWD Image Compression](http://filamentgroup.com/lab/rwd_img_compression/)

------

*Remember the design should always dictate the breakpoints and not the other way around.*

------

**Update 2013-05-14**

I must say I completely agree with Joni Korpi on his post [Leaving old IE behind](http://www.jonikorpi.com/leaving-old-IE-behind/) and also with Chris Ferdinandi in [Mobile First and Internet Explorer](http://gomakethings.com/mobile-first-and-internet-explorer/).

The Mobile first approach allows you to make a clean break with legacy browsers. By simply not wrapping the narrower/mobile layout  inside a media query you allow older browsers, that don't understand media queries at all to display the mobile design - which is usually a one column layout that focus on the page content. 

For modern browsers, that do support media queries you can then go crazy, and use all the modern techniques for structuring the page content and elements. 

**It's a win, win kind of deal.**

------

[This is Responsive](http://bradfrost.github.io/this-is-responsive/index.html), a website by Brad Frost that has a lot of great examples of responsive patterns as well as other responsive design resources.


**Update 2013-07-14**

Nothing ground breaking here but the following article gives a couple of really good suggestions on how to use SASS (or Less) to implement responsive design, the easy way.

- [Improve your responsive design workflow](http://www.netmagazine.com/tutorials/improve-your-responsive-design-workflow-sass)
