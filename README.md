[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LO5PCc12)
# Instructions

https://docs.google.com/document/d/1FQ8_7J8ZwtUmNAGYCSjdGhZWqdfgW86C0wREJ9Q3grE/edit?usp=sharing

# Issues identified with Manual Analysis:

1. Contrast:
    The color combination between the headings and background did not meet the accessibility standards which made it difficult for users with visual impairments to differentiate between the text and background. 

2. Font Size:
    Text was hard to read on smaller devices due to fonts sizes only declared in the default css.

3. Images:
    Use of PNG and higher file size was resulting in the page loading slower.


# Issues identified with Automated analysis:

Contrast Errors: Automated analysis identified low contrast between text and background in some areas of the pages.


# General Issues and Changes: 

Design: My initial color and font size decisions focused more on aesthetics over accessibility which impacted usability of my website. To improve the usability and accessibility of my website, I changed the background colors and ensure contrast ratios met the WCAG standards. I used media queries to scale fonts for smaller screens.

Responsiveness: The use of absolute units such as px for images and text made the site less functional on smaller devices. I changed the units to responsive units such as em and percentages which makes it easier to adjust the font sizes to via media queries. It makes it easier because these units are relative to the the parent container which allows content to adjust fluidly.

Webiste Load Time: Large image files led to the page loading slowly.








Contrast and font connect with Gestalt principles
in gestalt principles we discussec color and structure, having contrasting colors that are appealing and also accessible.