# SVG

## Prerequisites:
1. Knowledge of HTML
2. Text Editor

## Getting Started

In SVG, later elements are rendered atop previous elements.

SVG code can be embedded in the HTML code for HTML5 compliant browsers.

HTML files can be referenced like this.

```<object data="image.svg" type="image/svg+xml" />```

Likewise, iFrame can be used.
```<iframe src="image.svg"></iframe>```

SVG files can be saved as .svg or .svgz (gzip-compressed SVG).

For uploading to the server, use HTTP headers:
```Content-Type: image/svg+xml
	Vary: Accept-Encoding```

`For all elements, SVG uses Grid system with its origin(0,0) at the top left position.`