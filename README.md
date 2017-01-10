## Website Performance Optimization portfolio project

### Running the application:
To run the application first you need do download the code. You can download the ZIP file or clone this repository.

To download the ZIP file, click on the green button on this page that says "Clone or download" and then click on the "Download ZIP" button. After the ZIP file is downloaded, you need to unzip it in a folder that you find more convenient.

If you prefer to clone the repository, follow this instructions made by Github: [Cloning a repository](https://help.github.com/articles/cloning-a-repository/).

To run the application just click on the **index.html** file. It has to be opened by an internet browser like Chrome, Safari or Firefox.

### List of modifications

#### Part 1: Optimize PageSpeed Insights score for index.html

Changes made:
- Load the perfmatters.js in an async way
- Minify the perfmatters.js
- Get the essencial CSS (style.css) and move inside the HTML (inline)
- Move the non essencial css (print.css) to the end of the html
- Minify the CSS - [https://cssminifier.com/](https://cssminifier.com/)
- Download the external images and use them locally
- Download the fonts to use locally
- Resize and generate new images to optimize performance (pizzeria.jpg)
- Minify the HTML - [https://kangax.github.io/html-minifier/](https://kangax.github.io/html-minifier/)


#### Part 2: Optimize Frames per Second in pizza.html

Changes made:
- Made 2 changes to the main.js file to optimize the performance (lines 506 and 532).
- The first change made was moving some calculation to outside of the for loop.
- The second change made was remaking the way the pizza elements were inserted. There were too many elements, so I introduced a calculation to insert only the necessary number of elements. I also moved the style properties to the css and added a will-change property to the elements.
- Removed the determineDx function (line 424)
- Changed and optimized the changePizzaSizes function (line 427)