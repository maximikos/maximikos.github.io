+++
date = "2021-10-17"
title = "Hello, world!"
var"layout-post" = nothing
tags = ["welcome", "julia"]
rss = "Welcome to my personal academic website and my first blong entry!"

# Dependent variables
website_description = replace(rss, "*" => "")
rss_pubdate = Date(date)
+++

~~~
<h1><a href="{{ get_url }}">{{ markdown2html title }}</a></h1>
~~~

This is my first post! Time to celebrate &#127881;

Although I have been having the idea of creating a website for a long time, it took me until the start of my PhD to finally sit down and get going. Because I recently got interested in the [Julia](https://julialang.org/) programming language, I thought: "Why not try to use it for my website?" Luckily, there exists the package [Franklin](https://franklinjl.org) that allows to do exactly that. Even luckier, I came across [this pretty website](https://fredrikekre.se) by [Fredrik Ekre](https://github.com/fredrikekre), which I took as a template. And voilà! Here we go &#128512;.