# HTML Links, JS Functions, and Intro to CSS Layout

*Notes for chapter 4 and 15 from HTML and chapter 3 from JS to include "6 reasons for pair programming*

## Chapter 4 - HTML book

### Links

Links are features embeded in a website that allow you to move from one page to another, aka "Surfing" or "Browsing".
Common examples of links are:
- Links from one page to another on the same website
- Links that open in a new browser window, and
- Links from one website to another

You can creat links using the <a> tag. Users can click on anything set with in the opening <a> tag and the closing </a> tag. You can
be specific on what pages you want to link using the "href" attribute.
  
for example: ```<a href="http://imdb.com">IMDB</a>```

**Directiry structre**

The root folder contains all of the other files and folder for a website. The relationship between files and folders in a website can be discribed as a "family tree". The homepage of a site is writen with HTML and is called index.html. Web servers are set up to return the index.html file is it doesnt specify a name.

**Relative URLS**

When you link a page to your own site, you dont have to specity the domain name, just you relative URLs which is a short way to telling the browser where a page is.


## Chapter 15 - HTML book

### Layout

**Building Blocks**

CSS treats each HTML element as its own box. It'll either be a **Block-level** box or an **Inline** box. **Block-level** boxes start on a new line and act as the main building blocks of any layout, while the **Inline** boxes flow bwtween surrounding text.

**Containing Elements**

If one block-level sits in another block-level, then the outer box is known as the **Containing** or **Parent** element. 


## Chapter 3 - JS book

### Functions, Methods, and Objects

**What is a Function?**

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

To creat a function, you assign it a name and then write a statement needed to achieve its task inside the curly braces. This is known as a **function declerartion**.

For example: ```function sayHello() { document,write('Hello!'); }```

**Function** is the key word. **sayHello();** is the function name.




[<==back](README.md)
