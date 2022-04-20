---
layout: post
title: Practice Post
author: Lfrakie
categories: [ News ]
image: "/uploads/prtscr-capture_79.jpg"
tags: []


---
Practice post

site url:
{{site.url}}

page url:
{{page.url}}

site baseurl:
{{site.baseurl}}

page title:
{{page.title}}

replace - page url name:
{{page.title | replace: " ", "-"}}


base URL:
{{ site.baseurl }}



<a href="{{site.baseurl}}{{page.url}}index.html" download="{{page.title | replace: " ", "-"}}.odt.html">Download Text</a>

<iframe src="{{ site.baseurl }}{{ page.url }}" frameborder="0" style="overflow:hidden;overflow-x:hidden;overflow-y:hidden;height:100%;width:100%;position:absolute;top:0px;left:0px;right:0px;bottom:0px" height="100%" width="100%"></iframe>
