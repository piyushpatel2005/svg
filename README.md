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

For all elements, SVG uses Grid system with its origin(0,0) at the top left position.

### Demo of shapes

Check out shapes.svg. Most of the attributes are clear from the image presentation that you find.

c  - center
x - distance from x
y - distance from y

Only path element is totally different.It will allow us to create awesome images only using svg.

#### Path element

The "d" attribute contains a series of commands that allow a developer to draw complex images.
M = Move to
```M 10 10```  means move to (10, 10)

L = Line to
```L 10 20```  draws line to (10, 20) from current position.

H = Horizontal line
```H 20``` draws Horizontal line in positive X direction to the point (20, y)

V = Vertical line
``` V -30``` draws vertical line in positive Y-axis (towards top) which is reverse in web context. 

Z = Close path

#### Curve commands with Path

Q = Quadratic curve
It requires two points. The first one being the meeting point of the two tangents and the second one being the end of the curve.

A = Arc

A rx ry x-axis-rotation large-arc-flag sweep-flag x y






