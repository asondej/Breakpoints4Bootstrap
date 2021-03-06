# Breakpoints4Bootstrap
Bootstrap 4 breakpoints detector. Straightforward pure js class to detect current breakpoint and log it into console.

[![log breakpoint in console](https://github.com/asondej/Breakpoints4Bootstrap/blob/main/docs/breakpoints4bootsrap.gif)](https://asondej.github.io/Breakpoints4Bootstrap/)

[**[DEMO PAGE]**](https://asondej.github.io/Breakpoints4Bootstrap/)


## How to use?

Include breakpoint_detector.js file, preferably at the bottom of your HTML document.

```html
<script src="breakpoint_detector.js"></script>
```

Initialize  script like this:
```javascript
document.addEventListener("DOMContentLoaded", function() {
  let breakpoint = new BS4breakpoints();
  breakpoint.log();
});
```


## Settings

BS4breakpoints( **delay_time** (int), **log_prefix** (string) );

**delay** - throtting in ms. Dafault is 350.<br>
**log_prefix** - text to display before breakpoint's name. Default is "current breakpoint".

