Horiseon Marketing Agency wants their existing page/code to be udpated [Refactoring] to include accessibility standards.  This will ensure the website will better translate to assistive technologies.

MAIN OBJECTIVE: Update codebase that follows accessibility standard

TO ACHIEVE: website optimized for search engines

ACCEPTANCE CRITERIA:
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


Updates made to the code (summarized):
     WHEN I view the source code
        THEN I find semantic HTML elements
            -Utilized following: <header>,<nav>,<img>,<section>,<article>,<aside>,<footer>

    WHEN I view the structure of the HTML elements
        THEN I find that the elements follow a logical structure independent of styling and positioning
            -<articles> inside <sections> and <aside>
            -h tags cascade down, when needed

    WHEN I view the image elements
        THEN I find accessible alt attribute
            -alt attribute added to img elements
            -img element that is set by the class has an 'aria-label' in order for a description to be applied

     WHEN I view the heading attributes
        THEN they fall in sequential order
            -h tags cascade down, when needed

    WHEN I view the title element
        THEN I find a concise, descriptive title
         -<title>Horiseon Marketing Services</title>


Additional updates:
    -added comments describing each section updated
    -updated css .background with different height to align better with demo page
    -utilized <small> tag for copyright info
    -style.css reorganized as seen in sequential order in code
        -nested classes as needed
        -utilized comments in css to help explain
    -created repository on github and pushed through bash