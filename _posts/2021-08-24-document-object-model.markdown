---
layout: post
title:  "Document Object Model"
date:   2021-08-24 17:06:37 +1200
categories: WEB503 Labs
---


The DOM levels are referencing the position of the elements in the heirarchy of the document. As displayed below, `<div>` is the parent element and `<h1>` is the child element. `<div>` would be on level 1 of the DOM and `<h1>` would be on level 2 of the DOM. 
```
<div>
<h1>Hello</h1>
</div>  
```

## Nodes

Nodes are broken down into several types.<br> 
The `Document` node is the root document<br>
The `DocumentType` node is the document type such as html, js, css etc.<br>
The `Element` node is the most common node as it represents a tag such as `<h1>` or `<p>`<br>
The `Attr` node is an attribute tag such as `href`<br>
The `Text` node is the content of a element such as basic text.<br>
The `Comment` node is when using // or /* to make a comment.   <br>

## Journal

My experience has taught me that the DOM rapidly expands as a site develops. My approach to it, though potentially incorrect, grew rapidly to the point where I had to switch from going horizontal to vertical. For creating my DOM, I used draw.io, a website I found to be very useful for making graphs and diagrams. 

<img class="img-fluid" src="https://raw.githubusercontent.com/NMIT-GITHUB/web503-s2-21-lab-four-EzekielBrown/master/lab4tree.png?token=AS6EONMX76KSMRJKEBYCBQDBKFL5O" alt="DoM Tree">


You can find the repo for this lab [here][Lab-Four].

[Lab-Four]: https://github.com/NMIT-GITHUB/web503-s2-21-lab-four-EzekielBrown
