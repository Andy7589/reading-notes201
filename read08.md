# HTML/CSS

*Notes for Chatper 15 **"Layouts"***

### Controlling The Position of Elements

CSS had the following positioning schemes that allow you to control the layout of a page: normal flow,
relative positioining, and absolute positioning.
Examples of these positioins are:

- **Normal Flow ```postion:static```**
(*Every block-level element appears on  a new line, causing each item to appear lower down the page than
 the previous one.*)
- **Relative Positioning ```position:relative```**
(*This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom,
 or left of where it would have been placed*)
- **Absolute Postioning ```position:absolute```**
(*This postions the element in relation to its containing element*)
- **Fixed Positioning ```position:fixed```**
(*This is a form of absolute positioning that positions the element in relation to the browser window, as
 opposed to the containing element*)
- **Floating Elements ```float```**
(*Floating an element allows you to take that element out of normal flow and position it to the far left or right
 of a containing box*)
- **Overlapping Elements ```z-index```***
(*Using the **z-index** property, you can control which box appears on top. This can help with overlaping boxes*)

### Using The 960.GS Grid Framework

960.gs provides a style sheet that you can include in your HTML pages. 960.gs creats grids to layout pages.
Here is an example of a 960.gs layout out:

```<head>
  <title>Grid Layout</title>
  <link rel="stylesheet" type="text/css"
        href="css/960_12_col.css" />
  <style>See the right hand page</style>
</head>
<body>
  <div class="container_12 clearfix">
    <div id="header" class="grid_12">
      <h1>Logo</h1>
        <div id="nav">
          <ul>
            <li><a href="">Home</a></li>
            <li><a href="">Products</a></li>
            <li><a href="">Services</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Contact</a></li>
          </ul>
        </div>
      </div>
      <div id="feature" class="grid_12>
        <p>Feature</p>
      </div>
      <div class="artical grid_4">
        <p>Column One</p>
      </div>
      <div class="artical grid_4">
        <p>Column Two</p>
      </div>
      <div class="artical grid_4">
        <p>Column Three</p>
      </div>
      <div id="footer" class="grid_12>
        <p>&copy; Copyright 2011</p>
      </div>
    </div><!-- .container_12 -->
  </body> ```
  
  

[<==back](README.md)
