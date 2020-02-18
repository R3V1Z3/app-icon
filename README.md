# App Icon
Simple web app to create app icons for apps that don't have them. Best used for commandline/terminal applications as they typically wouldn't include app icons.

## TODO

- we'll need to start with a square container.
- as first step, we'll need to assemble a few SVGs we'll be using as templates.
- app will use a series of SVG images, each which will have a single text element.
- text the user enters will replace the content of that text element.

``` javascript
let text = "";
document.getElementById("text-id").textContent = text;
```