# Horiseon Marketing Agency (01-HTML-GIT-CSS_HOMEWORK)
## Description
Horiseon Marketing Agency wants their existing page/code to be udpated [Refactoring] to include accessibility standards.  This will ensure the website will better translate to assistive technologies.
- Update codebase that follows accessibility standard
    - To achieve website optimized for search engines
    - To better translate to assistive technologies
- This will ensure the website will serve both the company and its visitors
- What I learned...
    - Reviewing accessibility where a bit overwhelming, however the technology around helping disabled/impaired is pretty amazing and definitely something I have never thought about. The requirement puts a lot of context around 'why' we code properly considering accessiblity. At minimum, he assists with making decisions vs just making something 'work'.

## Table of Contents
- [Accessibility](#accessibility)
- [CSS Formatting](#css_formatting)
- [Accessibility Tests](#accessibility_tests)
## Accessibility
Utilized appropriate semantic tags to utilize accessibility elements.<br> Header, nav, img, section, article, aside, and footer were used for the HTML layout.  Alt tags were used on img files.  H tags were used in sequential, cascading forms.<br> Utilized Aria-Label for image file in order to label the background image.
## CSS_Formatting
style.css file was reorganized as seen in sequential order in code.
- Nested classes as needed
- Utilized comments in css to help explain decisions
- Increased font size for benefits class to pass a11y contrast test
## Accessibility_Tests
- Keyboard only navigation
    - open web page, tab to highlight nav item 1 (Search Engine Optimization), press 'Enter', link to correct SEO section of the page.
    - open web page, tab to highlight nav item 2 (Online Reputation Management), press 'Enter', link to correct ORM section of the page.
    - open web page, tab to highlighted nav item 3 (Social Media Marketing), press 'Enter', link to correct SMM section of the page.
- color contrast accessibility validtor
    - utilize website: https://color.a11y.com/Contrast/ and paste website to validate contrast
- accessibility validator
    - website: https://achecker.ca/checker/index.php and paste website to validate content