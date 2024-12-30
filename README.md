# Webpage Design Per Specs

This is a Codecademy full-stack developer path project to design a webpage per specs.

## Highlight

Applying DRY (don't repeat yourself) principle, all repeated property values pairs in the CSS file have been spun off into separate classes.

The advantage of that is that just by looking at the HTML file, we know what styles have been applied to each element.

This also helps with testing as both structure and style can be seen in the HTML file. So, testing is just a question of deleting and adding classes to ensure there's no redundant styling.

### Details

To elaborate, just by looking at the HTML file and comparing the webpage but not looking at the CSS file, we know the following:

* body uses seashell color for the text and has a black background
* header is full width, has a black background, uses flex display and justifies content with space between
* links have seashell color to override the default blue
* The hero image container has a padding of 69 pixels, uses flex display and justifies content center
* The hero image also uses flex display and aligns items center
* The h2 container aligns text center, has full width and a black background
* The container of the first three teas is 1000 pixel wide, uses flex display and justifies content with space around
* The tea images are 300 pixel wide
* The image captions align text center and have a top margin of 10 pixels
* The container of the bottom two teas is 650 pixels wide
* The location image uses flex display, justifies content and aligns items center
* The h2 tag has a bottom margin of 15 pixels
* The locations boxes are spread over 1020 pixels
* etc.
