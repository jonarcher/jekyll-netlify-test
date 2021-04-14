---
layout: page
title: About
permalink: /about/
---

# I MADE A CHANGE!
And it was good. But did it auto deploy on push? Did it heck.

As I suspected, that error from the original `netlify init` about a timeout occurring when creating a webhook on github was the problem. Had to do a `netlify unlink`, delete the Netlify site in their UI, then `netlify init` and make a "new" site which seemed to remedy everything. I think. This is the test!

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll
