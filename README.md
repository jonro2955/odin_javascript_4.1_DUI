# odin_javascript_4.1_DUI

A simple image slider carousel written in HTML, CSS and JS. 
Live preview: https://jonro2955.github.io/odin_javascript_4.1_DUI/

The essential mechanisms for the slider can be described as follows:
1) Several images of equal size are positioned absolutely inside a parent HTML container with relative positioning, and each image is given "left" css values in ascending amounts equal to the image sizes. This spreads the images out horizontally into a row.
2) The images' parent container has its "overflow" css value set to "hidden" to show only one image inside its borders.
3) The images' are given the css: "transition: left 0.3s" so that whenever their "left" css value is changed using JavaScript, the images move smoothly over a span of 0.3 seconds.
