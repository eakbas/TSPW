# TSPW: The Simple Pandoc-based Website

This is a static website generator based on a very simple template and
[pandoc](http://pandoc.org). It allows you write the content of your website
using (almost) plain text -- more correctly said, using pandoc's markdown syntax
-- and generates a static HTML5-valid website which can be deployed on a
webserver. I used TSPW to create my own
[website](http://www.ceng.metu.edu.tr/~emre/). 

## How to use 

To use TSPW, follow these steps: 

1. Make sure you have [pandoc](http://pandoc.org) installed. 
1. Download/clone the repository (i.e. `git clone
https://github.com/eakbas/TSPW.git`),  
2. Create the content of your website by editing the markdown (`*.md`) files, 
3. Run `make`.
4. A `build/` directory will be created automatically for you. You can deploy
(i.e. copy) the contents of this directory to your webserver, typically under
`public_html/` in your home directory.

If you skip the second step above, then you will get [this dummy
website](http://www.ceng.metu.edu.tr/~emre/TSPW). 

## Why create yet another static-site-generator?

There are many static site generators, e.g.  [Jekyll](https://jekyllrb.com/),
[Hakyll](http://jaspervdj.be/hakyll/), [pelican](http://blog.getpelican.com/)
and more. And all of them are great, much more capable than TSPW. However, they
are primarily intended for creating blog websites, and therefore, complicated to setup
and use for a simple personal academic website. For this reason, I wrote this
simple generator. 

Why not directly write HTML code? Simply because [markdown
syntax](https://daringfireball.net/projects/markdown/syntax) beats HTML syntax
and thanks to powerful markdown compilers such as [pandoc](http://pandoc.org), it is
possible to generate full websites from markdown files. It is much easier to
create content using markdown than using HTML. 

Please [drop me a message](http://www.ceng.metu.edu.tr/~emre/) if you find TSPW
useful and/or you use it in any way.
