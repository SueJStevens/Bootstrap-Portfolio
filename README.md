# Bootstrap-Portfolio
Bootcamp Assignment 8/11/2018 - Bootstrap-Portfolio

###By Design Elements###
container-fluid + css allows a full browser width for header and footer with a border bottom on header and border top on footer.

container allows for a very wide margin of header, content and footer

Logo is deliberately cut off at top by design.  This design element works properly on xl, lg, and md screens.  I was not able to get it to work on sm and xs.

I also was not able to get media responsive for the nav collapse to work properly with the logo on sm and xs with strictly bootstrap and resorted to @media in css.

VERY IMPORTANT NOTE TO TA's Grading:          
Bootstrap documentation allows for column wrapping.  See this link:  https://getbootstrap.com/docs/4.0/layout/grid/#auto-layout-columns
        If more than 12 columns are placed within a single row, each group of extra columns will, as one unit, wrap onto a new line.
        ***By Design, to make it easy to add content from a database in the future, I am choosing one row which will wrap all cards in the album when they exceed 12 columns***


###Style Sheets###
I've decided to separate the style sheets so that there is one for all shared elements (header, footer, fonts, etc.) and another for each individual html.  This will allow me to eventually have only one html for shared nav, header, footer.

###To Do###
Social Icons not linked
