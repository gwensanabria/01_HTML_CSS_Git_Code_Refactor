Changes to HTML
1.Changed indentation and spacing
2.Changed title from 'Website' to 'Horiseon | Online Managment'; more descriptive.
3.Changed the 'div class=header' to 'header'.
4.Changed the 'div' that held the navigation bar into 'nav'.
5.Chnaged 'div class=hero' to 'section id=hero'.
6.Changed 'div class=content' to 'section'.
7.Changed 'div class=*' to 'article id=*'; did for search-engine-optimization, online-reputation-management, social-media-marketing, benefit-lead, benefit-brand, benefit-cost.
8.Added alt tags to all the images.
9.Changed 'div class=benefits' to 'aside'.
10.Changed 'div class=footer' to 'footer'.
11.Removed 'class="online-reputation-management"' and 'class="social-media-marketing"'.

Changes to CSS
1.Changed '.header' to 'header'.
2.Changed '.header h1' to 'header h1'.
3.Changed '.header seo' to 'header seo'.
4.Changed to 'seo' to one that stands out more'
5.Changed '.header div' to 'header nav'.
6.Canged '.header div ul' to 'header nav ul'.
7.Changed '.header div ul li' to 'header nav ul li'.
8.Changed '.hero' to '#hero-image'.
9.Changed '.content' to 'section'
10.Changed '.benefits' to 'aside'
11.Grouped '.benefits-lead, .benefits-brand, .benefits-cost' into a single property value as '#benefits-lead, #benefits-brand, #benefits-cost'.
12.Grouped '.benefits-lead h3, -brand h3, -cost h3' into a single property value as h3.
13.Grouped '.benefit-lead img, -brand img, -cost img' into a single property value as '#benefits-lead img, #benefits-brand img, #benefit-cost img'.
14.Grouped '.search-engine-optimization, .online-reputation-management, .social-media-marketing' into a singe property value as '#search-engine-optimization, #online-reputation-management, #social-media-marketing'.
15.Grouped '.search-engine-optimization img, .online-reputation-management img, .social-media-marketing img' into a single property value as '#search-engine-optimization img, #online-reputation-management img, #social-media-marketing img'
16.Grouped '.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2' into a single property value as h2.
17.Changed '.footer' to 'footer'.
18.Changed '.footer h2' to 'footer h2'. 




```

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
