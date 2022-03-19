# Code Refactor Starter Code

## Purpose
Horiseon Marketing agency needed a webiste for their busienss that explains the services they provide and the benefits of using Horiseon. 

## Problems Solved
I refactored the code to make the webiste 1) load faster and 2) more accesible for all users. I have provided a list of the changes made below.  

## Refactors 
* added title to website 
* added comments to html & CSS 
* added semantic HTML elements 
* refactored CSS for the new semantic elements
* organized css to fall in sequential order  
* added classes & divs for services section and condensed the CSS for services section
* moved font family and color to body CSS selector to make code more DRY 
* added alt text to images -> making website more accessible
* moved hero image to html -> creating faster load times

## Lessons Learned 
I learned the importance of using semantic HTML elements to orginize the HTML file. I also learned that anchor links will only work if they are linked to an ID instead of a class. This project also allowed me to practice using DRY code, creating more generic classes that could be applied to similar sections which reduced the need for repetitive CSS code.  

## Challenges 
I added an <a> tag to the Horiseon logo in the header to make it so it would take you back to the home page. Doing so messed up the styling of the logo. I could have solved this by moving the "header h1 .seo" styling below the "header a" styling in the css sheet but I wasn't sure if that would be considered an illogical flow so I kept the styling as is and removed the <a> tags from the Horiseon logo.

## Built With 
* HTML 
* CSS 

## Website 
https://clarkspencerc.github.io/horiseon-marketing/

## Contributions 
Spencer Clark
Starter code contributor

