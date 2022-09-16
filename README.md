# Improve accessibility on Horiseon website

Implement the following user story:

* As a marketing agency, I want a codebase that follows accessibility standards so that our own site is optimized for search engines

## Acceptance Criteria

* When I view the source code, then I find semantic HTML elements.

* When I view the structure of the HTML elements, then I find that the elements follow a logical structure independent of styling and positioning.

* When I view the image elements, then I find accessible alt attributes.

* When I view the heading attributes, then they fall in sequential order.

* When I view the title element, then I find a concise, descriptive title.

## Fixes made to index.html

* Created title based on company name.

* Properly structured document with correct html elements (i.e.: changed "div class='header'" to "header"; changed "div" with "ul" to "nav"; changed "div class='hero'" to "section"; put seo section, reputation management section, and social media marketing section in "article"; put benefits section in "aside"; changed "div class='footer'" to "footer")

* Fixed functionality of Search Engine Optimization option in navigation by adding id="search-engine-optimization" tag before class="search-engine-optimization".

* Added alt attributes to images.

* Added notes before distinct sections for sake of clarity.

## Fixes made to style.css

* Created variables for color and font family that repeated 3 or more times.

* Changed all instances of .header to just header.

* Changed ".header div", ".header div ul", and ".header div ul li" (Lines 27, 35, and 39 in sample code respectively) to "header nav", "header nav ul", and "header nav ul li".

* Reordered rules to follow order of appearance in index.html (i.e: moved .content rules to directly underneath .hero's rule, etc.).

* Grouped shared rules.

* Changed all instances of .footer to just footer.

* Added notes before distinct sections for sake of clarity.

## Deployed Application
https://griffin-woodson.github.io/challenge-horiseon/

## Screenshot of Finished Webpage

![griffin-woodson github io_challenge-horiseon](https://user-images.githubusercontent.com/95516308/190545682-d9096bd7-16ed-48d8-8e6d-f1d61077ec2e.png)

