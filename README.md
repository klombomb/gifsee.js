# gifsee
A modern, vanilla JavaScript Facebook style gif previewer and loader. Inspired by [this jQuery plugin.](https://github.com/SodhanaLibrary/jqGifPreview)

### Install
For now gifsee only supports old fashioned scripts, but module support will be added very soon. Grab a copy of the latest version from the ```dist``` folder and add it to your page, or clone the entire repo. 
```html
<link rel="stylesheet" href="../gifsee.min.css">
<script src="../gifsee.js"></script>
```
### Usage 
```html 
<img src="frame.png" data-gifsee="gif.png" id="super-cool-gif">
```
```javascript
var myImage = new gifsee(document.getElementById('super-cool-gif'));
```
### Docs
**gifsee** ```new gifsee(HTMLImageElement)```  
*gifsee has one parameter which must be an Image element*  

**HTMLImageElement**  
*src*  
URL for an image preview of your Gif. (can be any image, but width should be the same a gif)

*data-gifsee*  
URL for gif.

### Demo
[Here](https://klombomb.github.io/gifsee.js/)
