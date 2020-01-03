# Welcome to where I rant about opengraphs

Oh my lord this is very confusing and hurting my brain. I've been trying to do this for months.  I'm just going to make a list of resources that I've used.

* [https://stackoverflow.com/questions/57493239/opengraph-link-previews-in-jekyll](https://stackoverflow.com/questions/57493239/opengraph-link-previews-in-jekyll)
* [https://stackoverflow.com/questions/8855361/fb-opengraph-ogimage-not-pulling-images-possibly-https?rq=1](https://stackoverflow.com/questions/8855361/fb-opengraph-ogimage-not-pulling-images-possibly-https?rq=1)

This should be all of the opengraph meta tags that I need.

```html
<meta property="og:title" content="soarn.pro" />
<meta property="og:description" content="soarn.pro" />
<meta property="og:image" content="https://soarn.pro/icons/favicon-194x194.png" />
<meta property="og:image:alt" content="soarn.pro logo" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://soarn.pro" />
<meta property="fb:app_id" content="804473663656626" />
<meta name="theme-color" content="#157878" /> <!--This applies a color to the embed, mainly noticable on Discord.-->
<link type="application/json+oembed" href="https://soarn.pro/embed.json" />
```
