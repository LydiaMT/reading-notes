### Chapter 10: Introducing CSS

* Imagine there is an invisable box around every HTML element
* Example styles: boxes, text, specific

```CSS
Selector {
    declaration property: declaration value;}
```

**External CSS**
Link element in HTML tells browser where to find the CSS file to style the page. lives in the head. href specifies the path. type specifies the type of doc being linked. rel specifies relationship

```HTML 
<link href="css/styles.css" type="text/css" rel="stylesheet" />
```

**Internal CSS**
You can include CSS rules within an HTML page by placing them inside a style element, usually in the head. Use this when building a site with more than one page. 

```HTML
<Style type="text/css">
```

**CSS Selectors**
See cheatsheet table on page 238. This is a great resource. 

**How Rules Cascade**
* If two selectors are identical, the latter of the two will take precedence
* If one is more specific than the other, the more specific one takes precedence
* You can always add !important

**Inheritance**
Children tags usually inherate parent tag properties. 

**Different versions of CSS & Browser quirks**
Always test your code in multiple browsers and different operating systems. 
* BrowserCam.com 
* BrowserLab.Adobe.com
* BrowserShots.org
* CrossBrowserTesting.com

### Chapter 11: Color

Color is a mix of read, green, and blue. Great cheatsheet on page 251-252

* Foreground Color: color of your text. You can use RGB (100,100,90), HEX Codes #000fff, or Color Names Blue.
* Background Color: Think of this as the color of the box your element is appearing in. If nothing specified, assumed transparent. 
* Contrast: High contrast is the most readable
* Opacity (CSS3): value between 0.0-1.0. You can always asign 'fall back' values for old browsers. The latter of the two rules will always take priority. 
* HSL Colors (CSS3): Hue 0-360, saturation 100%-0% i.e. full saturation to shades of gray, lightness 0%-100% i.e. black-white
* HSL & HSLA (CSS3): Stands for Hue, Saturation, Lightness. Hue is 0-360, Saturation is a %, and Lightness is a % with 0% being white and 100% being black. A stands for Alpha and represents transparency between 0.0 and 1.0. Good idea to add an extra rule which specifies color with hex code, RGB, or color name as a fallback. 

[⬅ Back to README Home](README.md)