# README
## Landing Project Udacity 
### the used language : 
- HTML, CSS3, ES6

 ### folder Structure :
- css: styles.css  
- index.html
- js: app.js
- README.md
### steps needed to make the project work:
- just download the file 

### Dynamic Nav-bar :
 The navigation is built dynamically as an unordered list.
### Scroll to Anchor
when **click** the name of the wanted section in the nav-bar it will scroll the page **smoothly** to that section thathas been choosen,

### Active Section:
- when you scroll the page down it highlight the part of the page that appear ,It is clear which section is being viewed while scrolling through the page.
- and return some properties related to viewport and the section by method called (getBoundingClientRect)

### Steps of the code : 
1. querySelectorAll used firstly to count the number of the sections
2. make a loop with forEach to loop through the sections to add <li> "list" , <a> "link" and textNode 
3. extract data-nav value from the section and store ot in a value called (paragraph) and set it to text content of each link
4. use (appendChild) on Fragment inside the loop
5. before ending the loop add eventListener (click) and use (scrollIntoView) to make the scroll smooth 
6. After ending of the loop append the fragment to ul (that stored in variable called myUL)
7. make function called active_link that take the value for the active section. 
8. Query all the links and store it in a variable called links and get the value by (getAttribute) for all the data-nav
9. make a loop with forEach to loop through the links and by using if condition to know which link has the textContent equal to active section data-nav.
10. Remove Active class from all links, give the active link class active.
11. make a loop with forEach to loop through the sections 
12. make variable called view to Use the getBoundingClientRect 
13. It will return some properties related to viewport and the section then 
14. Use if statement to know if the viewport inthe limits that you set, 
15. remove the other active classes from all sections.
16. Use classList.add method to add the active class to the active section.
17. add an EventListener to the window to highlight the active section when scrolling. 
