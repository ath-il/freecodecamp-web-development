# Heart Icon

A simple heart icon created using SVG (Scalable Vector Graphics) as part of a freeCodeCamp HTML workshop.

## What I Learned

### 1. `<svg>`

The `<svg>` element is used to create vector graphics directly inside an HTML document.

SVG graphics are based on mathematical shapes and paths, so they can be resized without losing quality.

```html
<svg width="24" height="24">
</svg>
```

### 2. `width` and `height`

The `width` and `height` attributes define the displayed size of the SVG.

```html
<svg width="24" height="24">
```

Here, the SVG is displayed at 24 pixels wide and 24 pixels high.

### 3. `viewBox`

The `viewBox` attribute defines the coordinate system used inside the SVG.

```html
viewBox="0 0 24 24"
```

The four values represent:

```text
min-x  min-y  width  height
  0      0      24     24
```

This means the SVG uses a coordinate system from `(0,0)` to `(24,24)`.

### 4. `fill`

The `fill` attribute defines the color used to fill an SVG shape.

```html
fill="red"
```

In this project, the heart is filled with red.

### 5. `<path>`

The `<path>` element is used to create complex custom shapes in SVG.

```html
<path d="..."></path>
```

A path can contain different drawing commands to create lines and curves.

### 6. `d` Attribute

The `d` attribute contains the instructions that tell SVG how to draw the path.

```html
d="M12 21s-6-4.35-9.33-8.22..."
```

Common path commands include:

* `M` — Move to a starting point
* `L` — Draw a straight line
* `C` — Draw a cubic Bézier curve
* `Q` — Draw a quadratic Bézier curve
* `S` — Continue a smooth curve
* `Z` — Close the path

The heart shape is created using these path commands.

## Output

❤️

A red heart icon is displayed on the webpage.

## Technologies Used

* HTML5
* SVG

## Project Structure

```text
heart-icon/
├── index.html
└── README.md
```

## Source

Created as part of the freeCodeCamp HTML curriculum.
