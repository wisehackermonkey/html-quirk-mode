# html-quirk-mode
----
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<img src="assets/2021-03-06-16-51-02.png" width="400">
<h2 align="center">my hacking/experimentation with the browser's 'quirks mode' to see what cool things i can do with it! </h2>

<!-- <h4 align="center">________________________</h4> -->



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

















<!-- ---------------------------------- -->
<!-- FULL -->
<!-- ---------------------------------- -->

<!-- # html-quirk-mode -->
<!-- ---- -->
<!-- 
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<img src="assets/NNNNNNNNNNNNN" width="400">
<h2 align="center">____________________</h2>
<h4 align="center">________________________</h4>
 -->

<!-- 

# Quick start
### __________________
##### __________________________
```bash
```

 -->


<!-- 

# Summary
### -  *[Quick start](#Quick-start)*
### -  *[Live Demo](#Live-demo)*
### -  *[Installation](#Installation)*
### -  *[Screenshots](#Screenshots)*
### -  *[License](#License)*
### -  *[Features](#Features)*
### -  *[For developers](#For-developers)*
### -  *[Todo](#TODO)*
### -  *[Related](#Related)*
### -  *[Contributors](#Contributors)*
 -->



<!-- ----------------- -->
<!-- <img src="assets/KKKKKKKKKKK" width="400"> -->
<!-- # [Live Demo](https://www._____________.com) -->





<!-- 
# Installation
### 
```bash
``` 
-->




<!-- 

-----------------
# Screenshots
- <img src="assets/_____________" width="400"> 
- 
-->



<!-- 

# Features
- [x] ______
- [ ] ______

-->


<!-- 
-----------------
# For developers
### 
```bash
```
 -->





<!-- -----------------
# TODO
- [x] ___________
- [ ] ___________ 
-->

<!-- 
-----------------
# Built with
- #### ________________
-->





<!-- -----------------
# Related 
### [_________](https://www.____________.com)
 -->






<!-- 
-----------------
# Contributors

[![](https://contrib.rocks/image?repo=wisehackermonkey/html-quirk-mode)](https://github.com/wisehackermonkey/html-quirk-mode/graphs/contributors)

##### Made with [contributors-img](https://contrib.rocks).

-----------------
# License
#### MIT © wisehackermonkey
[![MIT](https://img.shields.io/github/license/wisehackermonkey/html-quirk-mode.svg)](https://github.com/wisehackermonkey/html-quirk-mode/blob/master/LICENSE)
-->

<!-- 
```bash
by oran collins
github.com/wisehackermonkey
oranbusiness@gmail.com
______________________
``` 
-->

<!-- ---------------------------------- -->
<!-- EXTRAS -->
<!-- ----------------------------------- -->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<!-- 
[![Javascript](https://img.shields.io/badge/Javascript-Enabled-lightgreen.svg)](https://shields.io/) 
[![forthebadge made-with-python](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
![Python](https://img.shields.io/badge/Python-Enabled-<COLOR>.svg)
![P5.js](https://img.shields.io/badge/P5.js-Enabled-pink.svg)
[![Generic badge](https://img.shields.io/badge/<SUBJECT>-<STATUS>-<COLOR>.svg)](https://shields.io/)
[![GitHub release](https://img.shields.io/github/release/wisehackermonkey/html-quirk-mode.svg)](https://GitHub.com/wisehackermonkey/html-quirk-mode/releases/)
[![GitHub tag](https://img.shields.io/github/tag/wisehackermonkey/html-quirk-mode.svg)](https://GitHub.com/wisehackermonkey/html-quirk-mode/tags/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/wisehackermonkey/html-quirk-mode.svg)](https://GitHub.com/wisehackermonkey/html-quirk-mode/pull/)
[![Website perso.crans.org](https://img.shields.io/website-up-down-green-red/http/www.orancollins.com.svg)](http://www.orancollins.com/) 
    -->

<!-- 
# https://yuml.me/diagram/plain/activity/draw
### (start)->[AAAAAAAA]<aaaaa->(BBBBBB)->(end) 

# Diagram
## 
```bash
```
 -->

<!-- 

# List
- 
- 
- 

# Table
| XXX | YYYY |
|----- |-----|
| ___s | ____| 

| XXX  | YYYY |
|:-----|:-----:|
| ___s | ____| 


# Toggle List (NO FORMATTING)
<details><summary>AAAAAAAA</summary>
<details><summary>Hidden A</summary>
</details>
</details>

<details><summary>BBBBBBBBB</summary>
<details><summary>Hidden B</summary>
</details>
</details>

<details><summary>CCCCCCCCC</summary>
</details>



# Toggle list with formatting
<details><summary>Level 1</summary></details>

<details><summary>&emsp;BBBBBBBBB</summary></details>
<details><summary>&emsp;&emsp;CCCCCCCCC</summary></details>
<details><summary>&emsp;&emsp;&emsp;DDDDDDDDD</summary></details>


# Toggle list Nested
<details><summary>Level 1</summary>

<details><summary>&emsp;BBBBBBBBB</summary>
<details><summary>&emsp;&emsp;CCCCCCCCC</summary>
<details><summary>&emsp;&emsp;&emsp;DDDDDDDDD</summary>

</details></details></details></details></details></details></details></details></details></details></details></details></details></details></details></details></details></details>

# Keyboard Commnand
### <kbd>Command/ctrl + R</kbd> 

# Installation
### 
```bash
cd ~
git clone https://github.com/wisehackermonkey/html-quirk-mode.git
cd html-quirk-mode
pip install -r requirements.txt
npm install
```

# Docker
### Build
```bash
cd ~
git clone https://github.com/wisehackermonkey/html-quirk-mode.git
cd html-quirk-mode
docker build -t wisehackermonkey/html-quirk-mode:latest .  
```
### Run
```bash
docker run -it --rm --name wisehackermonkey/html-quirk-mode:latest  
```
### Docker-compose
```bash
docker-compose build
docker-compose up 
```



# Publish Docker Image
```bash
docker build -t wisehackermonkey/html-quirk-mode:latest .
docker login
docker push wisehackermonkey/html-quirk-mode:latest
```

 -->
