# Dynamic Web Pages with JavaScript

Three Languages work together to create web pages:
  - **html**
    - this is the content layer that provides structure and semantics to the web page
  - **css**
    - this is the presentation layer, with rules that state how HTML is presented to the audience
  - **javascript**
    - this is the behavior layer, which governs how the page behaves and makes it interactive for the user

Combining HTML, CSS, and JavaScript to build a web page is called __*progressive enhancement*__.

It is best practice to code HTML, CSS, and JavaScript in separate files
  - for troubleshooting purposes
  - to make reusing the code on multiple pages easier

## Linking to a JavaScript File from an HTML Page

To use JavaScript with a webpage written in HTML, you should use a **script element** 

    A script element tells the browser that it is coming across a script

    The src element tells where the JavaScript file is stored

In our text, Jon Duckett states that
>The HTML script element is used to load the JavaScript file into the page...it has an attribute called src, whose value is the path to the script created. 


#### Also, when linking the source code, the html remains the same.

 The source of the web page only shows the link to the JavaScript file, *not* the new element added to link the files. 

[**Return to Home**](README.md)