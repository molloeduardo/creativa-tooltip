# Creativa - Tooltip
This is a simple library that allows you to create awesome tooltips importing just one JavaScript file.
## Getting started
You can import the JS file in two ways:
1. Using the HTTPS link to the file: https://creativajs.altervista.org/tooltip/0.1/creativa-tooltip.js
2. With offline file. If you want to use the offline file just download the archive, import the **creativa-tooltip.js** file in your project and use it into your HTML.
## Examples
Basic example:
```
<html>
    <head>
        <script src="https://creativajs.altervista.org/tooltip/0.1/creativa-tooltip.js"></script>
        <title>Creativa Tooltip - Example</title>
    </head>
    <body>
        <a href="https://www.google.it/" ct-tooltip="Go to Google!" style="margin: 100px;">Hover me!</a>
    </body>
</html>
```
You can download the archive from GitHub and try the **example.html** file.
Or you can go here: https://creativajs.altervista.org/tooltip/0.1/example.html
## Where is the CSS?
The CSS will be automatically included from the **creativa-tooltip.js** file inside the HTML head. If this not happens or you want to use it locally, just import and use the CSS file too.
## Customizable
Every aspect of the tooltip is customizable.
## Tested browsers
- Chrome
- Firefox
- Microsoft Edge
- Safari

It doesn't work with the old Internet Explorer.
## Mobile
The tooltip works perfectly on mobile devices too. To do this, I implemented an event that disable the browser context menu on the tooltip elements.
## Attributes
### Simple tooltip
With the attribute **ct-tooltip** you can generate a simple tooltip that will appear on top of the link.
```
<a href="https://www.google.it/" ct-tooltip="Go to Google!">Hover me!</a>
```
### Tooltip position
You can specify the position of the tooltip with the **ct-tooltip-position** attribute.
```
<a href="https://www.google.it/" ct-tooltip="Go to Google!" ct-tooltip-position="right">Hover me!</a>
```
The allowed positions are the following:
- top (default)
- bottom
- right
- left
### Tooltip HTML
Inside the tooltip text you can use HTML tags too.
```
<a href="https://www.google.it/" ct-tooltip="Go to Google! <br> <b>Yes! You can use HTML too!</b>" ct-tooltip-position="right">Hover me!</a>
```
## Customization
Inside the **creativa-tooltip.js** file you can customize every aspect of the tooltip with the following settings.
```
animationSpeed: (default is 100)
openAnimationDelay: (default is 150)
borderRadius: (default is 5px)
backgroundColor: (default is #000)
color: (default is #fff)
fontSize: (default is 12px)
fontWeight: (default is 500)
lineHeight: (default is 16px)
```
