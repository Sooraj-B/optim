## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

steps to access the website:
1) U can download or fork the github repo. The link https://github.com/Sooraj-B/optim
2) The link to live website is https://sooraj-b.github.io/optim/

The list of changes i have done are:
1. Inline style.css to index.html.
2. Remove link to google fonts.
3. Compress and resize images.
4. Moved javascript tags (`script`) to the bottom of body.
5. Async javascript files.
6. Use media query for print.css.
7. Added a media query for portrait mode (index.html.61).
8. Made many changes to changePizzaSizes function in views\js\main.js.
9. Made many changes to updatePositions function in views\js\main.js.
10. A few changes to the class `mover` style.css in views\css\style.css.