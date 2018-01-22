# CSS Style sheets, latex templates, etc. for making documents look better

## The preferred way to make a document is to write in markdown (in vim) and to use pandoc to create a PDF or HTML page. Relevant commands are as follows:

* pandoc -s -c style/style.css -t html5 -o outputdocument.pdf inputdocument.text

* pandoc -o outputdocument.pdf inputdocument.text

## redirect.css

This style sheet is for squid's redirect pages (whenever I get squid working).

## syllabus-style.css

Is obviously a style sheet for syllabi. 

## Google provides lots of web fonts.

To use them, go to fonts.google.com. select a font. use google's code to embed it in your style sheet. proceed with pandoc as usual.

### for example

Use the google generated `@import ;` at the top of the stylesheet to import the fonts. Use the google generated font family line within the style sheet to select the imported font.

for example:

font-family: 'Miss Fajardose', cursive;
