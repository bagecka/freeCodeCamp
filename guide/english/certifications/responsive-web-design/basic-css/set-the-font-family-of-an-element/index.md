---
title: Set the Font Family of an Element
---
## Set the Font Family of an Element
<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
You can set the font family of a text with the font-family property. 

In CSS there are generic family names such as "Sans-serif" or "Monospace", as well as font family names such as "Helvetica" or "Comic Sans".

The font-family property normally holds several font names for the browser to fall back to. If the browser does not support the first font, it tries the next font, and so forth. When one font isn't available, you can tell the browser to "degrade" to the next font.

### Examples:
``` css
p {
    font-family: "Arial", sans-serif;
}
```
This example sets the font-family to "Arial" first, then to sans-serif if Arial is not available.

#### More Information:
<a href="https://www.w3schools.com/css/css_font.asp" target="_blank">W3schools: CSS Fonts</a><br>
