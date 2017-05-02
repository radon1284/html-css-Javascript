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

### All CSS Border Properties

| property | Description                                                               		|
|----------|--------------------------------------------------------------------------------|
| border				| Sets all the border properties in one declaration 				|
| border-bottom			| Sets all the bottom border properties in one declaration			|
| border-bottom-color	| Sets the color of the bottom border 								|
| border-bottom-style	| Sets the style of the bottom border 								|
| border-bottom-width	| Sets the width of the bottom border 								|
| border-color			| Sets the color of the four borders 								|
| border-left			| Sets all the left border properties in one declaration 			|
| border-left-color		| Sets the color of the left border 								|
| border-left-style		| Sets the style of the left border 								|
| border-left-width		| Sets the width of the left border 								|
| border-radius			| Sets all the four border-*-radius properties for rounded corners 	|
| border-right			| Sets all the right border properties in one declaration 			|
| border-right-color	| Sets the color of the right border 								|
| border-right-style	| Sets the style of the right border 								|
| border-right-width	| Sets the width of the right border 								|
| border-style			| Sets the style of the four borders 								|
| border-top			| Sets all the top border properties in one declaration 			|
| border-top-color		| ets the color of the top border 									|
| border-top-style		| Sets the style of the top border 									|
| border-top-width		| Sets the width of the top border 									|
| border-width			| Sets the width of the four borders 								|

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

### CSS Padding

The CSS `padding` properties are used to generate space around content.

The padding clears an area around the content (inside the border) of an element.

With CSS, you have full control over the padding. There are CSS properties for setting the padding for each side of an element (top, right, bottom, and left).

CSS has properties for specifying the padding for each side of an element:

```html
padding-top
padding-right
padding-bottom
padding-left
```
All the padding properties can have the following values:

* ***length*** - specifies a padding in px, pt, cm, etc.
* ***%*** - specifies a padding in % of the width of the containing element
* ***inherit*** - specifies that the padding should be inherited from the parent element

```css
p {
    padding-top: 50px;
    padding-right: 30px;
    padding-bottom: 50px;
    padding-left: 80px;
}
```

### CSS Height and Width

The `height` and `width` properties are used to set the height and width of an element.

The height and width can be set to auto (this is default. Means that the browser calculates the height and width), or be specified in length values, like px, cm, etc., or in percent (%) of the containing block.

```css
div {
    height: 200px;
    width: 50%;
    background-color: powderblue;
}
```

### Setting max-width

The `max-width` property is used to set the maximum width of an element.

The `max-width` can be specified in length values, like px, cm, etc., or in percent (%) of the containing block, or set to none (this is default. Means that there is no maximum width).

The problem with the `<div>` above occurs when the browser window is smaller than the width of the element (500px). The browser then adds a horizontal scrollbar to the page.

Using `max-width` instead, in this situation, will improve the browser's handling of small windows.

```css
div {
    max-width: 500px;
    height: 100px;
    background-color: powderblue;
}
```

### The CSS Box Model

ll HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

![border-style](https://dl.dropboxusercontent.com/u/24437921/box-model.png?raw=true)

### CSS Outline

The CSS `outline` properties specify the style, color, and width of an outline.

An outline is a line that is drawn around elements (outside the borders) to make the element "stand out".

However, the outline property is different from the border property - The outline is NOT a part of an element's dimensions; the element's total width and height is not affected by the width of the outline.

![border-style](https://dl.dropboxusercontent.com/u/24437921/outline.png?raw=true)

### Outline Style

The `outline-style` property specifies the style of the outline.
The `outline-style` property can have one of the following values:

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

![outline-style](https://dl.dropboxusercontent.com/u/24437921/outline-sample.png?raw=true)

### CSS Text

The color property is used to set the color of the text.

With CSS, a color is most often specified by:

* a color name - like "red"
* a HEX value - like "#ff0000"
* an RGB value - like "rgb(255,0,0)"

| property 			| Description                                                               																			|
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| color				| Sets the color of text 																																|
| direction			| Specifies the text direction/writing direction 																										|
| letter-spacing	| Increases or decreases the space between characters in a text 																						|
| line-height		| Sets the line height 																																	|
| text-align		| Specifies the horizontal alignment of text 																											|
| text-decoration	| Specifies the decoration added to text 																												|
| text-indent		| Specifies the indentation of the first line in a text-block 																							|
| text-shadow		| Specifies the shadow effect added to text 																											|
| text-transform	| Controls the capitalization of text 																													|
| text-overflow		| Specifies how overflowed content that is not displayed should be signaled to the user 																|
| unicode-bidi		| Used together with the direction property to set or return whether the text should be overridden to support multiple languages in the same document 	|
| vertical-align	| Sets the vertical alignment of an element 																											|
| white-space		| Specifies how white-space inside an element is handled 																								|
| word-spacing		| Increases or decreases the space between words in a text 																								|

### CSS Fonts

The CSS font properties define the font family, boldness, size, and the style of a text.

![fonts](https://www.w3schools.com/css/serif.gif?raw=true)

### CSS Font Families

In CSS, there are two types of font family names:

* ***generic family*** - a group of font families with a similar look (like "Serif" or "Monospace")
* ***font family*** - a specific font family (like "Times New Roman" or "Arial")

### All CSS Font Properties

| property 		| Description                                                               |
|---------------|---------------------------------------------------------------------------|
| font			| Sets all the font properties in one declaration							|
| font-family	| Specifies the font family for text										|
| font-size		| Specifies the font size of text											|
| font-style	| Specifies the font style for text											|
| font-variant	| Specifies whether or not a text should be displayed in a small-caps		|
| font-weight	| Specifies the weight of a font											|

```css
p {
    font-family: "Times New Roman", Georgia, Serif;
}

h2 {
    font-size: 200%;
}
p.normal {
    font-style: normal;
}

p.italic {
    font-style: italic;
}

p.oblique {
    font-style: oblique;
}
p {
font-variant: normal|small-caps|initial|inherit;
}
p {
font-weight: normal|bold|bolder|lighter|number|initial|inherit;
}
