# Jorge's Website
Okay so the only thing you should have to do is post new stories and new photos on the website, so I'll teach you how to do that here.

First before you make a post it is worth nothing that these files will be Kramdown files so they are not like your typical text document.

Like a normal text document when you type it shows up but in order to make a new line you have to write <br />. Hitting enter will be ignored. Secondly there are a bunch of cool features that I put down below called "Kramdown Cheat Sheet."
Secondly, whenever you write a story or want to post a picture you have to create a document exactly like this.

year-mm-dd-Title-Seperated-by-dashes.md

it has to end in .md not .txt or .doc or anything else
and the first lines in your document have to be
```
---
layout: post
title: "Sample post"
date: year-mm-dd
categories: story
---
```
if it is a story or
```
---
layout: post
title: "Picture of Cat"
date: year-mm-dd
categories: picture
---
```
I'll leave sample documents in the sample folder.
I'll make a video and post it on youtube.
How to

```
Kramdown Cheat Sheet

<p> This is how you should seperate paragraphs</p>
<p> New Paragraph here</p>

<p>To do line breaks you <br />
which forces a line break</p>

Now lets go over how to use headers
<h1>H1 header</h1>

<h2>H2 header</h2>

<h3>H3 header</h3>

<h4>H4 header</h4>

<h5>H5 header</h5>

<h6>H6 header</h6>

how to make a block quote

    >This is a block quote!
    >more quotes by Carlos
    >kldsjfks

<blockquote>
This is also a block <br />
quote!
</blockquote>

<ol>
  <li>This is a list item</li>
  <li>And another item</li>
  <li>And the third one
with additional text</li>
</ol>

<ul>
  <li>This is a list item</li>
  <li>And another item</li>
  <li>And the third one
with additional text</li>
</ul>

<p>Finally you add links like this linked below is my reference to krandown's website.<br />

<p><a href="https://kramdown.gettalong.org/quickref.html">You can brush up here too!</a>
</p>
```
