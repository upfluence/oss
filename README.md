# OSS (117)

![Mr Bonisseur de La Bath](http://flat-tv.net/uploads/posts/2015-07/1437715605_agent-117.jpg)


## Why

Because!
Well, that's not a useful answer. Here's a better one. That project came in my mind while reading a lot of articles (remind me to stop reading Medium and Smashing Magazine) about User Experience and User Interfaces (which — I cautiously admin — I really love!).

The idea was then to have a standardized/branded styleguide and design across all of our projects; so that users will have the same amazing experience while browsing trough our applications. As we talk, some of those design are handled by Ember UPF Utils, but more on the Ember components side than the CSS one.

Plus, our softwares designs has been mainly decided by tech people, leading to something far from ugly (despite our unconditional love for CSS), but also not as UXy as it could be.

## How It Works

Having a design and graphical charter is good! Actually it's really really good !
But so far, only the Corporate Website is following it.

What i had in mind then is to build upon the new graphical charter to have a set of good looking elements to use in our products. By elements there, i mean reusable components that are always seen across projects (wether they are just raw HTML or custom Ember Component). For example, a `button` is a component, a `link` is a component, just as a `Summernote` is a component too. And in my mind, they should have exactly the same look and feel whether they are on Upfluence Search (Facade) or in Publishr.

So, how does it really work? Well: CSS classes (Yay!). A piece of code being worse a million words, I will let you browse the `app/styles` folder.

* `base` folder will contain all stylesheets related to basic HTML elements (forms, buttons, links, whatever); each element having it's own file.
* `components` folder will contain all component-related stuffs (Summernote, for example).

Even better if you want to actually see what it looks like. This is an Ember app, so you can run it.

Go `ember serve` and you will have all the component that have been built yet.


## Further Reading / Inspirations

[How we created a frontend framework — Marsbased] (https://marsbased.com/blog/2017/01/27/How-We-Created-Frontend-Framework-Marsman-Template/)

[Form Validation Best Practices] (https://medium.com/@andrew.burton/form-validation-best-practices-8e3bec7d0549#.xs8hxtd0x)

[Web Developer guide to colors — Smashing Magazine] (https://www.smashingmagazine.com/2016/04/web-developer-guide-color/)

[Creating style guides — A List Apart](http://alistapart.com/article/creating-style-guides)