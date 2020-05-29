# Code Refactor

## Description
The client - a marketing agency - requested that their website be refactored, so that it is accessible to its users. In order to make the website meet accessibility standards for their user base, all the "div" tags were removed from the original code and were transformed into the appropriate semantic HTML5.

## Attaining Web Accessibility 
To attain web accessibility: the "head" tags were replaced with "header" tags; the "div class="content"" was reformatted for a "main" tag (since it is dominant content for the users); each "div id" tag was changed into an appropriate "section" tag; the "hero" tag was exchanged for a "figure" element as it is self-contained content; all non-semantic elements were removed from the original code. (I grouped certain sections and images together in order to condense the code since the characteristics of certain sections - such as margins and alignments - were the same.)