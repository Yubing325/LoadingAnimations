# LoadingAnimations
Some web loading animations effect I wrote via using HTML/CSS + JQuery

### demo1
this demo shows how to set the loading animations with a specific time (3s in my example).

note
: this is not the best practice, but for some case it's handy.

### demo2

this demo shows how the loading animations faded out as soon as the web page is rendered.  It's more pratical than demo1 because it's not set by time.

note: please clean your cache during test otherwise the effect may be less significant to notice.

### demo3

this demo using CSS3 to build the animations. CSS3 is greater than GIF loading methods in terms of the size and execution time.

### demo4

this demo shows a top-fixed bar loading animations and when the page was loaded, it's fade out automatically. You can cusomize the color and bar height in stylesheet.


### demo5 - CSS3 & JQuery Percentage display

This demo shows a complicated loading animations based on the real loading process and display percentage loading.

In this demo the `new Image()` object , `complete` property , `onload, onerror, onkeydown, onkeypress` Event was being used.

> note: be sure to put `src` behind the `onload` event to avoid display error in IE brower.