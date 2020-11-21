# README1
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
2. make a loop with forEach to loop through the section to add <li> "list" , <a> "link" and textNode 
3. extract data-nav value from the section and store ot in a value called (paragraph) and set it to text content of each link
4. use (appendChild) on Fragment inside the loop
5. before ending the loop add eventListener (click) and use (scrollIntoView) to make the scroll smooth 
6. After ending of the loop append the fragment to <ul>  (that stored in variable called myUL)
