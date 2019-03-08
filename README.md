jquery.simplePaint.js
==========
[![MIT License][license-image]][license-url]

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE

### Simple jQuery Drawing App

### Last version:
* 1.0.0

### Support:
* Paint Options:
  - pen
  - shapes
    - line
    - triangular
    - rectangle
    - circle
   - text
   - background image
 * more buttons options:
   - undo/redo
   - eraser
   - save as image
   - clear
   - colors
 * and more ... see demo

### Demo
* See demo <a href="http://meshesha.js.org/simplePaint/" target="_blank">here</a>.

###  usage:
 include necessary css files:
 ```
<link rel="stylesheet" href="jquery.simplePaint.css">
```
 include necessary js files:
 ```
<script type="text/javascript" src="./path/to/jquery.min.js"></script>
<script type="text/javascript" src="jquery.simplePaint.js"></script>
 ```
 html body :
 ```
 ...
   <div id="your_div_container"></div>
 ...
 ```
 add javascript:
 ```
<script type="text/javascript">
 $("#your_div_container").simplePaint({
    width: "600px", /*in pixel only*/
    height: "450px", /*in pixel only*/
    buttons: [], /*options: ["pen", "line", "triangle", "rect", "circle", "text", "eraser", "undo", "redo", "clear", "image", "save"]*/
    canvasBgColor: "rgb(224, 239, 253)" /*cnavas background color*/
 });
</script>
 ``` 

 
###  Changelog:
 v.1.0.0:
 - first releases
