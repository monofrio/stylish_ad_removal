# Stylish Ad Removal
---
The main start of this project was that I was getting tired of having Ads cut up articles and making them difficult to read.
Just create a new style sheet and add in the css and save it.


Stylish extention for [Chrome](https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en)
, [Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/), or [Safari](http://sobolev.us/stylish/)

```
/* Amazon */
    iframe[src*="amazon"],

/* Facebook */
    div[class="fb_iframe_widget"],

/* Global */
    .ad, #ad,
    div[id*="adzerk"],
    .dontPrint,
    .kskdDiv,
    .IL_BASE,
    iframe[id*="ox_"],
    div[data-ad-name],
    ins[id*="aswift"],
    iframe[id*="aswift"],
    #aswift_1_expand,

/* Google */
    .GoogleActiveViewClass,
    div[id*="google"],
    iframe[id*="google"],
    ins.adsbygoogle,

/* Taboola */
    div[id*="taboola"],

/* Yahoo */
    div[data-component="yahooAdSearch"],

/* zz slider */
    #zzcontent,
    #zzsliderlayer_box

    {display:none !important;}

```