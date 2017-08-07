# Roboto Fonts - Complete
+ Roboto [Default](https://fonts.google.com/specimen/Roboto)
+ Roboto [Condensed](https://fonts.google.com/specimen/Roboto+Condensed)
+ Roboto [Slab](https://fonts.google.com/specimen/Roboto+Slab)
+ Roboto [Mono](https://fonts.google.com/specimen/Roboto+Mono)
+ Material Icons - [Guide](http://google.github.io/material-design-icons/)

# How to use
You must include the css files for the font you want to use.

### For instance
CSS
```css
/* Full support for older versions */
@import "node_modules/roboto-latin/css/Roboto/Thin.css";
@import "node_modules/roboto-latin/css/Roboto/Thin-Italic.css";
/* Alternative - and recommended */
@import "node_modules/roboto-latin/css/Roboto/Thin-Woff.css";
@import "node_modules/roboto-latin/css/Roboto/Thin-Italic-Woff.css";
```

## Google Fonts CDN - Latin
HTML
```html
<!-- Default -->
<link href="https://fonts.googleapis.com/css?family=Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i" rel="stylesheet">
<!-- Condensed -->
<link href="https://fonts.googleapis.com/css?family=Roboto+Condensed:300,300i,400,400i,700,700i" rel="stylesheet">
<!-- Slab -->
<link href="https://fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700" rel="stylesheet">
<!-- Mono -->
<link href="https://fonts.googleapis.com/css?family=Roboto+Mono:100,100i,300,300i,400,400i,500,500i,700,700i" rel="stylesheet">
<!-- Icons -->
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
```
CSS:
```css
body
{
  font-family: 'Roboto Condensed', sans-serif;
  font-family: 'Roboto Mono', monospace;
  font-family: 'Roboto Slab', serif;
  font-family: 'Roboto', sans-serif;
  font-family: 'Material Icons';
}
```
## NPM
```bash
npm install --save roboto-latin
```
## Bower
```bash
bower install --save roboto-latin
```
# Tools and resources
+ [BramStein](https://github.com/bramstein)
+ [Article about: Flash Of Invisible Text (FOIT)](https://calendar.perfplanet.com/2016/loading-web-fonts-asynchronously/)
+ [Bulletproof syntax](https://calendar.perfplanet.com/2016/no-font-face-bulletproof-syntax/)
+ [Roboto on Google Fonts](https://fonts.google.com/?query=Roboto)
+ [Google Font Converver - ttf to woff2 (g++)](https://github.com/google/woff2)
+ [Font Converter](https://onlinefontconverter.com/)
+ [Stackoverflow - ttf, eot, woff, woff2, svg](https://stackoverflow.com/questions/11002820/why-should-we-include-ttf-eot-woff-svg-in-a-font-face#answer-11002874)
