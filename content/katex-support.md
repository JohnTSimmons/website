+++
title = "Adding Katex Support"
date = 2024-09-06

+++

Self-notes on adding Katex support to this website. Should work for other Zola themes as well.

<!--more -->

# Config Changes

In the [extra] category katex_support and katex_auto_render bools are added and need to be set to true.

# Head Template

In the head template for the html pages there is a new if statement that checks for katex_support to be true, and if it is it adds the script tags necessary to make Katex function. Unfortunately this introduces Javascript to the website, but it works and only took a few minutes to implement.

# Usage

Create a katex block with the following snippet: (remove the space between the k and atex in line one.)

```html
{% k atex(block=true) %}

x = y^2 log(z){cases}

{% end %}
```

The above line would render as:

{% katex(block=true) %}

x = y^2 log(z)

{% end %}



A bug I need to fix is that multiline Katex expressions do not render properly...

# Update 2024-09-09

Removed Katex support by setting config changes to false. Mainly because I wanted to go back to an entirely Javascript free site, and I could not figure out why the katex block rendering wasn't functioning correctly. 
