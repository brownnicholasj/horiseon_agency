Horiseon Marketing Agency wants their existing page/code to be udpated [Refactoring] to include accessibility standards.  This will ensure the website will better translate to assistive technologies.

MAIN OBJECTIVE: Update codebase that follows accessibility standard

TO ACHIEVE: website optimized for search engines

ACCEPTANCE CRITERIA:<br>
    WHEN I view the source code<br>
        THEN I find semantic HTML elements<br>
    WHEN I view the structure of the HTML elements<br>
        THEN I find that the elements follow a logical structure independent of styling and positioning<br>
    WHEN I view the image elements<br>
        THEN I find accessible alt attributes<br>
    WHEN I view the heading attributes<br>
        THEN they fall in sequential order<br>
    WHEN I view the title element<br>
        THEN I find a concise, descriptive title<br>

Updates made to the code (summarized):<br>
     WHEN I view the source code<br>
        THEN I find semantic HTML elements<br>
            -Utilized following: header,nav,img,section,article,aside,footer<br>
<br>
    WHEN I view the structure of the HTML elements<br>
        THEN I find that the elements follow a logical structure independent of styling and positioning<br>
            -articles inside sections and aside<br>
            -h tags cascade down, when needed<br>
<br>
    WHEN I view the image elements<br>
        THEN I find accessible alt attribute<br>
            -alt attribute added to img elements<br>
            -img element that is set by the class has an 'aria-label' in order for a description to be applied<br>
<br>
     WHEN I view the heading attributes<br>
        THEN they fall in sequential order
            -h tags cascade down, when needed<br>
<br>
    WHEN I view the title element<br>
        THEN I find a concise, descriptive title<br>
         -title>Horiseon Marketing Services/title><br>
<br>
Additional updates:<br>
    -added comments describing each section updated<br>
    -updated css .background with different height to align better with demo page<br>
    -utilized small tag for copyright info<br>
    -style.css reorganized as seen in sequential order in code<br>
        -nested classes as needed<br>
        -utilized comments in css to help explain<br>
    -created repository on github and pushed through bash<br>
    -commits were lower as I setup an initial repository and completed work -- I did something within the settings of the repository and I was having issues resolving, so I created a new repository and moved the completed work to new repository with 'first commit'