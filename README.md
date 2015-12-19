
# swap-svg-JQplugin

 Jquery plugin to Swap Images with svg src with inline svg Elements.
 
### The Problem.
 
 If you've ever used svg icons, you would have added it as an source, like so.
 
 ```
 <img src="circle.svg" />
 ```
 
 this takes away all the editability of the svg. you cannot use css selectors, etc.
 
### The solution

the plugin swaps this

 ```
 <img class="swap-svg" id="myid" src="circle.svg" />
 ```
 
 ```
 <svg class="swap-svg" id="myid" xmlns="http://www.w3.org/2000/svg" version="1.1" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="none" x="0px" y="0px" width="330px" height="400px" viewBox="0 0 330 400">
......
</svg>
```
now you can use your css selector to change colors, etc.

#### Usage.

just initiate the plugin.

```
$(".swap-svg").swapSvg();
```



 
