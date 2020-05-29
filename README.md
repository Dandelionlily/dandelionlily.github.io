# dandelionlily.github.io

Carol's crafts is a simple website to show photographs of Carol's crafting projects. It contains four html files.

The index.html page has an unordered list of navigation links to the other pages. It also contains a brief about-the-author.

All other pages have a navigation bar at the top and display photos with "like" and "favorite" buttons underneath. These buttons change colors on rollover and click.

The sculpey.html page contains photos of sculpey figurines and links to external websites.

The amigurumi.html page contains photos of crocheted dolls. It also contains a table of changes that need to be made for the dolls to be baby-safe.

The costumes.html page sizes the Captain Marvel images based on an @media query. It also uses a Bootstrap badge ("new").

All four pages are styled by Bootstrap and by styles.css, which is automatically compiled from styles.scss.



Requirements:

  At least 4 different .html pages (index.html, sculpey.html, amigurumi.html, costumes.html)
  
  It should be possible to navigate between all pages in the website following hyperlinks (Table of Contents on index.html; navigation bar on other pages)
  
  At least one list (Table of Contents in index.html)
  
  At least one table (Baby-safe Substitutions table in amigurumi.html
  
  At least one image (sculpey.html, amigurumi.html, costumes.html)
  
  At least one stylesheet (styles.css)
  
  Stylesheet contains at least 5 different CSS properties (text-align, margin, width, border, border-collapse, ...)
  
  Use the #id selector at least once (#marvel-costume, #marvel-sweatshirt)
  
  Use the .class selector at least once (.favorite-button, .like-button)
  
  At least 5 different types of CSS selectors: 
    element selector (h1), 
    multiple element selector (#marvel-costume, #marvel-sweatshirt), 
    descendent selector (table th), 
    child selector (nav > a), 
    pseudoclass selector (%message-button:hover)
    
  At least one responsive @media query for screen size (@media (min-width: 991px))
  
  Use Bootstrap 4:  
    at least one Bootstrap component (class="badge"), 
    at least two Bootstrap columns (class="col-sm", class="col-lg")
    
  Use Sass for at least one variable ($wide-screen), 
    at least one nesting (table { th {}}), 
    at least one inheritance (.like-button {@extend %message-button;})
  
