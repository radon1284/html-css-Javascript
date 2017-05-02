### stylesheets
***CSS*** = cascading style sheets

cascading style sheets are now the standard way to define the presentation of your HTML pages, from fonts and colours to the complete layout of a page. They are much more efficient than using HTML on every page to define the look of your site.

CSS is becoming a more important language to know every day, so the sooner you have a grip on this most elegant of presentational languages, the better.

### There are three types of CSS styles:

***Inline styles*** 
are styles that are written directly in the tag on the document. Inline styles affect only the tag they are applied to.

```html
<a href="#" style="text-decoration: none;">
```

***embedded styles***
Embedded styles are styles that are embedded in the head of the document. Embedded styles affect only the tags on the page they are embedded in.

```html
<style type="text/css">
p { color: #00f; }
</style>
```

***external styles***
External styles are styles that are written in a separate document and then attached to various Web documents. External style sheets can affect any document they are attached to.

CSS best practices recommends that you use primarily external style sheets for styling Web pages so that you get the most benefit of the cascade and inheritance.

```html
<link rel="stylesheet" type="text/css" href="styles.css" />
```

### CSS Syntax

![properties](https://www.w3schools.com/css/selector.gif?raw=true)

Sample:

```css
p {
    color: red;
    text-align: center;
}
```

### CSS Colors

Colors in CSS are most often specified by:

* a valid color name - like "red"
* an RGB value - like "rgb(255, 0, 0)"
* a HEX value - like "#ff0000"

```css
h1 {
    color: #ff0000;
}
```

### CSS Backgrounds

The CSS background properties are used to define the background effects for elements.

***CSS background properties:***

* background-color
* background-image
* background-repeat
* background-attachment
* background-position

```css
body {
    background-color: lightblue;
}
```

### CSS Border

The CSS border properties allow you to specify the style, width, and color of an element's border.

The `border-style` property specifies what kind of border to display.

| property | Description                                                               |
|----------|---------------------------------------------------------------------------|
| dotted   | Defines a dotted border                                                   |
| dashed   | Defines a dashed border                                                   |
| solid    | Defines a solid border                                                    |
| double   | Defines a double border                                                   |
| groove   | Defines a 3D grooved border. The effect depends on the border-color value |
| ridge    | Defines a 3D ridged border. The effect depends on the border-color value  |
| inset    | Defines a 3D inset border. The effect depends on the border-color value   |
| outset   | Defines a 3D outset border. The effect depends on the border-color value  |
| none     | Defines no border                                                         |
| hidden   | Defines a hidden border                                                   |

Sample:
![border-style](https://dl.dropboxusercontent.com/u/24437921/border-style.png?raw=true)

### CSS Margins

The CSS `margin` properties are used to generate space around elements.

The margin properties set the size of the white space outside the border.

With CSS, you have full control over the margins. There are CSS properties for setting the margin for each side of an element (top, right, bottom, and left).

CSS has properties for specifying the margin for each side of an element:

```html
margin-top
margin-right
margin-bottom
margin-left
```

All the margin properties can have the following values:

* ***auto*** - the browser calculates the margin
* ***length*** - specifies a margin in px, pt, cm, etc.
* ***%*** - specifies a margin in % of the width of the containing element
* ***inherit*** - specifies that the margin should be inherited from the parent element

***Tip:*** Negative values are allowed.
