---
title: Set the id of an Element
---
## Set the id of an Element
<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
In addition to class attributes, each HTML element can also have an id attribute. The id attribute specifies a unique id for an HTML element and must be unique within the HTML document; it is best practice to never give more than one element the same id attribute.

You can use an id to style a single element, or the value can be used by CSS and JavaScript to select and modify specific elements with the specified unique id value. In CSS, to select an element with a specific id you type # followed by the id of the element.

### Examples:
``` html
<style>
#specialText {
    background-color: grey;
    color: black;
    padding: 10px;
    text-align: center;
} 
</style>
```
The avbove example uses CSS to select an element with a specific id by typing # followed by the id of the element.

``` html
<h2 id="specialText">Special Text</h2>
```
The above example shows that this h2 element has now been assigned the id of "specialText".

#### More Information:
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Applying_color" target="_blank">MDN web docs: Applying color to HTML elements using CSS</a><br>
<a href="https://www.w3schools.com/html/html_id.asp" target="_blank">W3schools: HTML The id Attribute</a><br>
