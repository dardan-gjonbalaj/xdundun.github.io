---
layout: post
title:      "Javascript DOM manipulation and learning more about performance"
date:       2020-06-06 19:46:04 +0000
permalink:  javascript_dom_manipulation_and_learning_more_about_performance
---


Javascript is your broker and it must make a good first impression. It cannot be late, it cannot be slow, it must get to the point, be engaging and sharp. It has to communicate with things that are very powerful and very responsive to it, and it also must communicate with those that are "out-dated" and maybe disinterested. By things I mean devices like your new iphone 11, or someones 10 year old laptop. The point I'm getting at is someone like myself isn't really thinking about these limitations being around such powerful technology and that's a mistake. A pilot may still enjoy manually landing a plane even though auto-pilot exists or just like grandma can't be bothered with changing devices! 

Making my SPA application to be a simple "store-front" I learned some things like not relying on DOM manipulation not only made some things easier, it just made them faster! Initially, I had my edit function for name and material (fake data provided by LoremPixel) to create `<input>` elements for both , create a new `<button>` for save, attach an event listener to that button, take the `element.value` if anything was or wasn't added or changed, it would submit the change based on value. Now after this has happened, it should go back to the original view. Not only is it more work to do within a specific `<div>`, I would achieve the same goal by creating a view-state or edit-state! Not that there was anything wrong with manipulating the dom with such small data, but what if I wanted to add things or change things around?

By changing my thinking to that, I realized that I covered a multitude of ground. I would do that work initially for every single element to provide the view state, it would be "cheaper" to call the edit state with just a function and all this without having to worry about traversing the dom tree so carefully. Using google chrome's console, I was able to verify it being faster under the network tab.

A great site for helping me see how sites are rated is [](http://https://developers.google.com/speed/pagespeed/insights/) and it excites me to think about these things and improving on them moving forward!
