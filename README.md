# html-quirk-mode
----
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<img src="assets/2021-03-06-16-51-02.png" width="400">
<h2 align="center">my hacking/experimentation with the browser's 'quirks mode' to see what cool things i can do with it! </h2>

<h4 align="center">Last updated 20210326</h4>



# Summary
<!-- ### -  *[Quick start](#Quick-start)* -->
<!-- ### -  *[Installation](#Installation)* -->
### -  *[Notes](#Notes)* -->
### -  *[Contributors](#Contributors)*
### -  *[License](#License)*




# Installation
```bash
```

<!-- ----------------- -->
<!-- # Screenshots -->
<!-- - <img src="assets/_____________" width="400">  -->
<!-- -  -->



<!-- SETUP -->
-----------------
# Notes
### I was looking at how to have html respect line breaks when someone mechined to check if the browser is running in quirks mode.
#### [css - How to preserve line breaks in <code> block? - Stack Overflow](https://stackoverflow.com/questions/1011641/how-to-preserve-line-breaks-in-code-block)
```text
Check your doctype is valid and on the first line. Maybe it's slipping into quirks mode?

```
### What is `quirks mode`?
### i have never heard of quirks mode before. Here is my experimeination with quirks mode.
### link to wiki page [Quirks mode - Wikipedia](https://en.wikipedia.org/wiki/Quirks_mode)
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
```
### within the dom how to check if the browser is running in quirks mode or not
```javascript
console.log(document.compatMode);
```
-----------------
# Example of quirk mode
![](assets/2021-03-06-16-51-02.png)
# Example of standard mode (what broswers normally do)
![](assets/2021-03-06-16-54-00.png)

# examples of backCompat
![](assets/2021-03-06-17-06-49.png)
# Notice the `table cell 2` is now correct color
![](assets/2021-03-06-17-07-40.png)

----
<br><br><br><br><br>
# Weird html stuff volume 1
```html
<!DOCTYPE HTML PUBLIC '''what">
```
![](assets/2021-03-06-17-42-01.png) 

# how Get html comments from within javascript
### link [Traversing the DOM - W3C Wiki](https://www.w3.org/wiki/Traversing_the_DOM)
![](assets/2021-03-06-17-56-44.png)
```javascript
document.childNodes[0]
//or
console.log(document.childNodes[0])
```

---------------


# Cool live dom viewer website link
# [Live DOM Viewer](https://software.hixie.ch/utilities/js/live-dom-viewer/)
---------------

---------------
# cool animated favicon demo
#### [Canvas-Favicon Circular Loader](https://rpsthecoder.github.io/favicon-canvas-loader/)
#### github repo [rpsthecoder/favicon-canvas-loader: Create and display a circular loading <canvas> animation as a webpage favicon.](https://github.com/rpsthecoder/favicon-canvas-loader)

# Werid behavior with html
![image](https://user-images.githubusercontent.com/29699356/112690533-2893ff80-8e39-11eb-9082-693710f93f73.png)
![image](https://user-images.githubusercontent.com/29699356/112690549-36498500-8e39-11eb-92a6-4a0d31a3e2f6.png)
```html

document.write('<style>#__f.__f{display:inline-block;text-align:left;}#__f.__f .counter{font-family:Ubuntu,Helvetica,Arial,sans-serif;line-height:1.4;box-sizing:border-box;width:130px;color:#565656}#__f.__f .c__h{font-size:10px;padding:5px 7px;border:1px solid #dedede;background:#fff}#__f.__f .c__t{text-transform:uppercase}#__f.__f .c__t span{float:right}#__f.__f .c__b{font-size:9px;padding:8px;background:#dedede}#__f.__f .c__b a{text-decoration:none;color:inherit}#__f.__f .c__b a:focus,#__f.__f .c__b a:hover{text-decoration:underline;color:inherit}#__f.__f .c__b a:focus{text-decoration:none}#__f.__f .c__i{margin-top:3px}#__f.__f .c__i:first-child{margin-top:0}#__f.__f .c__g{font-size:14px;font-weight:700;position:relative;display:block;margin-top:4px;padding:8px 5px;text-align:center;text-transform:uppercase;color:#04c;border:1px solid #fff;border-radius:3px;background-image:linear-gradient(to top,#e1dfdf 0,#fff 100%)}#__f.__f .c__g span{position:relative;display:inline-block}#__f.__f .c__g span:before{position:absolute;right:0;bottom:0;left:0;display:block;content:\'\';border-top:1px dotted #04c}#__f.__f .c__g:hover{text-decoration:none;color:#04c;background-image:linear-gradient(to top,#fff 0,#e1dfdf 100%)}#__f.__f .c-t__default .c__h{border-color:#dedede}#__f.__f .c-t__default .c__b{background:#dedede}#__f.__f .c-t__red .c__h{border-color:#e27e7e}#__f.__f .c-t__red .c__b{color:#fff;background:#e27e7e}#__f.__f .c-t__blue .c__h{border-color:#d7f3ff}#__f.__f .c-t__blue .c__b{background:#d7f3ff}#__f.__f .c-t__yellow .c__h{border-color:#ffecb1}#__f.__f .c-t__yellow .c__b{background:#ffecb1}#__f.__f .c-t__green .c__h{border-color:#a9c971}#__f.__f .c-t__green .c__b{color:#fff;background:#a9c971}#__f.__f .c-t__magenta .c__h{border-color:#ddc5e5}#__f.__f .c-t__magenta .c__b{background:#ddc5e5}.h{display:none}</style>');document.write('<div id="__f" class="__f"><div class="counter c-t__default"><div class="c__h"><div class="c__t">Total Hits <span>3</span></div><div class="c__t">Unique visitors <span>1</span></div></div><div class="c__b"><div class="counter__item">Powered by<br> <a href="https://freecountercode.com">Free Counter Code</a></div><div class="counter__item"><a href="http://glasvezelvergelijken.org/" class="h">glasvezelvergelijken.org</a></div></div></div></div>');
```
### [https://freecountercode.com/service/](https://freecountercode.com/service/EUBtzl21DpKzXW5XptnE/5201)

# Contributors

[![](https://contrib.rocks/image?repo=wisehackermonkey/html-quirk-mode)](https://github.com/wisehackermonkey/html-quirk-mode/graphs/contributors)
##### Made with [contributors-img](https://contrib.rocks).

-----------------
# License
#### MIT © wisehackermonkey
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
```bash
by oran collins
github.com/wisehackermonkey
oranbusiness@gmail.com
______________________
```






