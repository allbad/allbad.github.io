---
layout: post
title: Reflecting on Intro to HTML
---

Just taking the chance to add my concept deliberations on P1 submission.

What is the DOM?

The DOM provides a programming interface which defines the logical structure
for HTML and XML documents and defines the way that the documents can be
built accessed and manipulated.

[and W3C explanation]
(http://www.w3.org/TR/DOM-Level-2-Core/introduction.html}

Semantic vs. Non-Semantic
-------------------------

Non-semantic tags are those such as <div> and <span> (without the addition of
accompanying class or id tags to provide information about its content) and
provide only detail on how markup should look or be structured and offers no
meaning or context to the markup that it surrounds.  They would be used when
you need to provide something to differentiate the text from the surrounding
such as its hierachy and arrangement within the page.

Semantic tags, particularly those included in HTML5 such as <header> and
<footer> clearly define the meaning and content of the markup they surround.

Layout Principles
-----------------

A grid based layout priciple is one in which there is a division of layout
horizontally or vertically (mainly vertical) which uses guidelines that
incorporate margins, spaces and columns with the goal of providing a framework
to organise and provide consistency to the content of a website and to assist
with scaling the page to the appropriate display medium.

Despite being around for a few years, the flexbox principle appears to be
gaining a lot of interest lately and some see this as the future of web layout
when the specifications settle down and it is supported across the gamut of
browsers.  It is interesting as it looks to offer a much more flexible
approach than traditional grid layouts but reducing the complexity.  The main
issue to adoption at the moment seems to be that pages will load slower in
most cases due to horizontal misalignment and shifting as the page is loading.
The grid layout module will hopefully address this when it gets wide browser
support.

Responsive Design
-----------------

Responsive design is an approach using fluid layout and media queries which
optimises the layout of a site for various sizes of devices using the same
code and content without the requirement for separate website properties.
Only one codebase is needed regardless of which device is rendering the website.

### For HTML
<meta name="viewport" content="width=device-width">
### For CSS (and iPad 3+)
@media screen and (-webkit-min-device-pixel-ratio: 2) and (min-device-width:
768px)

Separation of Concerns
----------------------

HTML defines the structure and content of a page and CSS the style of that
page.  Firstly separating these into discreet files makes them smaller and
therefore load faster.  Separating these also allows us to easily edit parts
of the code without inadvertently affecting unrelated parts.  Thirdly it
allows for efficiencies of code where one CSS file may be used to style many
HTML pages without having to repeat all the styling information for each page.

Code Quality
------------

Code that is easy to read is not only easier to understand, debug, and
maintain by the developer writing it, but also it allows easier collaboration
on the code by other developers and for others to pick up and maintain if the
original developers are no longer around.

Providing a style guide allows the course evaluators to grade the course
projects consistently accross all students and to minimise any confusion due
to subjectivity of how to write and style websites. I cannot say whether every
company dictates styles, but would say that most effective companies do.
Style guides establish and enforce style to improve consistency and best
practice.
