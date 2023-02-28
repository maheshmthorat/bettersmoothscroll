# Better Smooth Scroll

A _**lightweight**_ and _**very fast**_ javascript library that provides enriched versions of the browsers' scrolling APIs with support for _**smooth-scrolling**_, _**callbacks**_ and many other features.

_**Multiple scroll-animations**_ on one or more containers can be played at the same time with full controll over them.

_**Every scroll-animation**_ triggered by the API _**can be interrupted**_ at any time and supports user-defined _**custom ease**_ functions.
This API is also fully compatible with _**Typescript, React.js, Next.js**_ and many other javascript frameworks.

## Playground

https://bettersmoothscroll.web.app/

## Installation

### Install with WordPress </> [DOWNLOAD NOW](https://downloads.wordpress.org/plugin/better-smooth-scroll.0.2.zip)

### Install other platforms </>

```html
<script async src="https://bettersmoothscroll.web.app/src/bettersmoothscroll.js?v=0.0.1"></script>
<style>
  body,
  html {
    margin: 0 !important;
    overflow: hidden !important;
  }
  body {
    width: 100vw !important;
    height: 100vh !important;
  }
  /* This is for the scroll bar  */
  .scroll-bar,
  [data-uss="scrollbar-track-y"] {
    background-color: #cccccc;
    z-index: 99999 !important;
    width: 1% !important;
  }

  /* This is for the scroll thumb */
  .scroll-bar div,
  [data-uss="scrollbar-thumb-y"] {
    background-color: #6936f5;
  }
</style>
```

## Author

- [@Mahesh Thorat](https://maheshthorat.web.app/)

## Support

If you want to support my work you can simply make a donation. For donations you can either use [this link](https://pages.razorpay.com/maheshmthorat). Support is appreciated but it's not compulsory in any way in order to use any of my work.
