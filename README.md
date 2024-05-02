# Checker Html

Defines the main articles of the Checker Html projects.
Articles equate to Svelte components, i.e. .svelte files

## Articles
Components:
* [Checker Projects](#checker-projects)
* [Checker Project Summary](#checker-project-summary)

### Checker Projects
A collection of individual [Checker Project](#checker-project-summary)'s
Components:
* [Checker Project Summary](#checker-project-summary)

### Checker Project Summary
* Followup Action (optional)

## CSS Grid Reference Projects

### ~/css-grid/Mobile-First-CSS-Grid-master
https://github.com/nabendu82/Mobile-First-CSS-Grid  
* Mobile First CSS Grid
* CSS Variables, grid, flexbox
* @media screen and (min-width: 960px){  - laptop
* @media screen and (min-width: 1200px){ - desktop 

### ~/css-grid/mobile-first-practice-project 
https://github.com/kamalahmed/mobile-first-practice-project
* Similar to ~/css-grid/Mobile-First-CSS-Grid-master
    * Slightly more complex but with more features
    * Better mobile menu
    * Mobile go to top of page button
    
### ~/css-grid/ecommerce-layout - photos
https://github.com/tomphill/ecommerce-layout

### ~/css-grid/responsive-tables
* grid-template-columns: repeat(auto-fit, minmax(var(--column-width-min), 1fr));
https://www.freecodecamp.org/news/https-medium-com-nakayama-shingo-creating-responsive-tables-with-pure-css-using-the-grid-layout-module-8e0ea8f03e83/    - very good but more complicated than checker-projects
https://codepen.io/ShingoNakayama/pen/LMLeRZ - very good example, uses cards for mobile
Also page 15 css-grid-layout
Additional grid tracks are created or removed depending on how much space is available, and the auto-placed items are reflowed.
This is achieved by using the auto-fill keyword instead of a number before the comma in our repeat notation.
Combining repeat, autofill with a minmax() minimum value of 200px and a maximum value of 1fr distributes any leftover space across the tracks that have been created.
Thus we get as many flexible tracks as will fit into our container, with a minimum size of two hundred pixels.

### ~/css-grid/book-code/css/css-grid-layout/2e/ch1-auto-fill-flexible.html -responsive boxes
* grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
https://github.com/abookapart/css-grid-layout-code/blob/master/2e/ch1-auto-fill-flexible.html

### ~/css-grid/book-code/css/css-grid-layout/2e/ch2-boxy.html, ch2-boxy-responsive.html - responsive images
The CSS object-fit property is used to specify how an <img> or <video> should be resized to fit its container.
img { object-fit: cover;  border-radius: 10px ; display: block; max-width: 100%; max-height: 100%; } 

https://github.com/abookapart/css-grid-layout-code/blob/master/2e/ch2-boxy.html
The CSS object-fit property is used to specify how an <img> or <video> should be resized to fit its container.
img { object-fit: cover;  border-radius: 10px ; display: block; max-width: 100%; max-height: 100%; }

### ~/css-grid/book-code/css/css-grid-layout/2e/ch3-layout.html

### ~/css-grid/book-code/css/css-grid-layout/2e/ch4-flex.html
### ~/css-grid/book-code/css/css-grid-layout/2e/ch4-grid.html
### ~/css-grid/book-code/css/css-grid-layout/2e/ch4-layout.html

### ~/css-grid/HTML-AND-CSS-MOBILE-UI-LAYOUT
https://github.com/MbuguaCaleb/HTML-AND-CSS-MOBILE-UI-LAYOUT
* Basic - CSS Grid and CSS Variables but not very good mobile 

### Online examples and info

* https://yoksel.github.io/grid-cheatsheet/ - 
* https://csslayout.io/patterns/
* https://scotch.io/tutorials/deep-dive-into-css-grid-2
* https://ishadeed.com/article/css-grid-minmax/

richard:checker-html richardhancock$ find . -type f -name "*.html"
./index.html
./grid.html
./examples/responsive-tables/dist/index.html
./examples/responsive-tables/src/index.html
./examples/HTML-AND-CSS-MOBILE-UI-LAYOUT/index.html
./examples/Mobile-First-CSS-Grid-master/index.html
./examples/css_nested_grid/index.html
./examples/2e/ch1-auto-fill.html
./examples/2e/ch1-line-based-grid-area.html
./examples/2e/ch1-auto-rows.html
./examples/2e/ch2-boxy-overlay.html
./examples/2e/ch1-line-based-overlap.html
./examples/2e/ch1-line-based-span.html
./examples/2e/ch3-layout.html
./examples/2e/ch1-fr.html
./examples/2e/ch1-line-based-named-lines.html
./examples/2e/ch1-line-based.html
./examples/2e/ch1-gaps.html
./examples/2e/ch2-boxy-responsive.html
./examples/2e/ch1-auto-fill-flexible.html
./examples/2e/ch1-minmax.html
./examples/2e/ch1-repeat.html
./examples/2e/ch4-grid.html
./examples/2e/ch5-nosubgrid.html
./examples/2e/ch4-layout.html
./examples/2e/ch1-grid-template-areas.html
./examples/2e/ch4-flex.html
./examples/2e/ch1-basic.html
./examples/2e/ch5-subgrid.html
./examples/2e/ch1-line-based-shorthand.html
./examples/2e/ch2-boxy.html
./examples/2e/ch2-layout.html
./examples/mobile-first-practice-project/index.html
./examples/ecommerce-layout/index.html
./checker-projects/checker-projects.html


### TODO
* Mobile Hamburger Menu
* Confirm layout for Projects, Project, Worklots, Checklists, Checkpoints, Criteria, Followup Actions

October-November Power Bil

