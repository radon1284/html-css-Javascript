### What is HTML?

**HTML** = *Hypertext Markup Language*

HTML is a computer language devised to allow website creation. These websites can then be viewed by anyone else connected to the Internet. It is relatively easy to learn, with the basics being accessible to most people in one sitting; and quite powerful in what it allows you to create.

### How does it work?

HTML consists of a series of short codes typed into a text-file by the site author — these are the tags. The text is then saved as a html file, and viewed through a browser. eg.(`index.html`).

### What are the tags up to?

The tags are what separate normal text from HTML code. You might know them as the words between the `<angle-brackets>`. They allow all the cool stuff like images and tables and stuff, just by telling your browser what to render on the page. Different tags will perform different functions. The tags themselves don’t appear when you view your page through a browser, but their effects do. The simplest tags do nothing more than apply formatting to some text, like this:

Example:
```html
<strong>These words will be bold</strong>, and these will not.
```
### Basic Structure

```html
<!DOCTYPE>
```
The DTD (Document Type Declaration), this tells your browser which version of HTML you're using. Make sure you use the right DTD, or your page may display incorrectly.

```html
<html>...</html>
```
Standard opening and closing tags for any HTML page. Enclose everything else in these. Container tag.

```html
<!-- ... -->
```
A comment — whatever you put here will be skipped over by the browser.
```html
<head>...</head>
```
Starts the header part of your document. Everything between these is mainly used to help your browser and search engines classify your page. Using this is optional, but recommended. Container tag.
```html
<title>...</title>
```
Whatever is between these tags will appear in the blue bar at the top of the screen.
```html
<meta>
```
A group of tags that give page and creator information specifically to the search engines.
```html
<base>
```
Changes the default link target or relative link URL, useful if the page is read on another server.
```html
<link>
```
Allows you to associate stylesheets and a favorites icon to your page.
```html
<body>...</body>
```
Everything visible on your page goes between these tags. Everything. Container tag.

standard html page

```html
<!DOCTYPE html>
  <html lang="en">
    <head>
    <title>My Page Title</title>
    <meta name="description" content="Your Description">
    </head>
    <body>
    <h1>Header 1</h1>
    </body>
  <html>
```

### Links

```html
<a>...</a>
```
Makes the enclosed text or image a hyperlink to another file.

### Lists

```html
<ol>...</ol>
```
Creates an ordered list, where each item is numbered in order. Container Tag.

```html
<ul>...</ul>
```
Creates an unordered list, with each item bulleted. Container Tag.

```html
<li>
```
Each list item begins with an li, and they are all placed in either an ol or ul.

```html
<dl>...</dl>
```
Creates a definition list.

```html
<dt>
```
Creates a definition term.

```html
<dd>
```
Creates a definition, which appears below its parent term and indented from the left.

Sample:
```html
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```

### Multimedia

```html
<img>
```
Places an image on your page
```html
<embed>
```

Adds a multimedia element directly into your page, allowing your browser to play it with a plug-in.

```html
<script>...</script>
```
Adds a script, usually a JavaScript into your page.

```html
<noscript>...</noscript>
```
Enclose anything you want displayed by browsers that do not support scripts.


### Tables

```html
<table>...</table>
```
Places a table on your page. Container Tag.

```html
<caption>...</caption>
```
contains the caption of the table, the title of sorts. It will appear across the top unless specified otherwise. This tag should not be contained in a tr or td.

```html
<tr>...</tr>
```
starts a new table row. Cells go inside this. Attributes are the same as td's.

```html
<td>...</td>
```
encloses a table cell. Content goes in these.

```html
<th>...</th>
```
same as table cells, but with all contents bold and aligned to the centre.

```html
<thead>...</thead>
```
Defines the header part of a large table. Wrap the tags around the rows/cells you wish to define as the header.

```html
<tbody>...</tbody>
```
Defines the main body of a complex table.

```html
<tfoot>...</tfoot>
```
Wrap this around the footer part of your table.

```html
<colgroup>
```
Allows you to set attributes for the entire column. Each column has to be defined sequentially.

Sample:
```html
<table>
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
  <tr>
    <td>5869207</td>
    <td>My first CSS</td>
    <td>$49</td>
  </tr>
</table>
```

### Frames

```html
<frameset>...< /frameset>
```
Starts a new frame layout. When constructing a frame page, no body is used. Container Tag.

```html
<frame>
```
Defines a single frame within a frameset.

```html
<noframes>...< /noframes>
```
If a visitor has an old browser which doesn't support frames you can leave a message or some content between these tags.

```html
<iframe>...</iframe>
```
Places an inline or 'floating' frame. This can be placed anywhere on a normal page, i.e. it doesn't need to be part of a frameset.

### Forms

```html
<form>...</form>
```
Begins a form area. Add in any form elements you want to use between these tags. Container Tag.

```html
<input>
```
Allows you to add various user input fields, like text-boxes, checkboxes, radio buttons, submit and reset buttons, depending on how you set the type attribute.

```html
<textarea>...</textarea>
```
Adds a multi-lined text area, suitable for input of a larger amount of information than the single-line text box. Any text added between the tags is placed in the area when the page loads.

```html
<select>...</select>
```
Sets up an empty drop-down selection box. You can add choices with the `html<option>...</option>` tag.

```html
<fieldset>...</fieldset>
```
Allows you to group form elements together into logical arrangements.

```html
<legend>...</legend>
```
You can title your fieldsets with this tag.

```html
<label>...</label>
```
You can make the explanatory text next to a form element into part of the clickable area with this tag, which makes selecting elements much easier.

### Text Formatting

```html
```
<address>...</address>
Encloses the signature and address of the author, displayed in italics.

```html
<b>...</b>
```
Makes the enclosed text into bold text.

```html
<big>...</big>
```
Makes the enclosed text one size bigger.

```html
<blockquote>...</blockquote>
```
Indents the text in from both sides.

```html
<br>
```
Stops the current line and goes on to the next.

```html
<center>...</center>
```
Aligns the surrounded objects (anything from text or images to forms etc.) to the center.

```html
<cite>...</cite>
```
Includes a citation, and is usually rendered as italics.

```html
<code>...</code>
```
If you are including either computer or HTML code into your documents wrap these around it. It is rendered in small text.

```html
<dfn>...</dfn>
```
A definition. As usual with these things, rendered in italics.

```html
<div>...</div>
```
Surround distinct sections of your page in divs, primarily to align them, but many other attributes are supported and divs can be used to set up layers too.

```html
<em>...</em>
```
Emphasises the surrounded text, changing it to italics.

```html
<font>...</font>
```
Sets the font properties for the selected text.

```html
<hx>...</hx>
```
Sets the text as a heading, with values of `h1` (the biggest) to `h6` (the smallest).

```html
<hr>
```
Inserts a grey horizontal line across the page.

```html
<i>...</i>
```
The default tag for italics.

```html
<kbd>...</kbd>
```
Implies that the text should be entered on the keyboard. It is rendered mono-spaced and small.

```html
<nobr>...</nobr>
```
Tells the enclosed text not to wrap at the edge of the screen, but continue on as long as it needs.

```html
<wbr>
```
If you need a line break in a block of text you have set in nobr, add this.

```html
<p>...</p>
```
Makes the enclosed text a paragraph, with lines skipped at the top and bottom.

```html
<pre>...</pre>
```
Displays text in fixed-width font and retains the formatting of the original text (i.e. spaces and line-breaks).

```html
<q>...</q>
```
Used to mark up short, inline quotations. Some browsers will add quotation marks around the text.

```html
<s>...</s> (or <strike>...</strike>)
```
Displays the text with a strike-through.

```html
<samp>...</samp>
```
Indicates sample output from a form or program. Text is rendered in small font.

```html
<small>...</small>
```
Makes the enclosed text one size smaller.

```html
<strong>...</strong>
```
Creates emphasis for the selected text, rendered in bold.

```html
<sub>...</sub>
```
Renders the text in subscript, which is words under the normal text. For example: this

```html
<sup>...</sup>
```
The sister tag to `<sub>` above, this renders text in superscript. Like this

```html
<tt>...</tt>
```
Renders text in fixed-width, mono-spaced font; like an old typewriter.

```html
<u>...</u>
```
Displays the surrounded text underlined.

### What is New in HTML5?

```html
<!DOCTYPE html>
```
The DOCTYPE declaration for HTML5 is very simple:

```html
<meta charset="UTF-8">
```
The character encoding (charset) declaration is also very simple:


### New Elements in HTML5

```html
<article>
```
Defines an article in a document

```html
<aside>
```
Defines content aside from the page content

```html
<bdi>
```
Isolates a part of text that might be formatted in a different direction from other text outside it

```html
<details>
```
Defines additional details that the user can view or hide

```html
<dialog>
```
Defines a dialog box or window

```html
<figcaption>
```
Defines a caption for a `<figure>` element

```html
<figure>
```
Defines self-contained content

```html
<footer>
```
Defines a footer for a document or section

```html
<header>
```
Defines a header for a document or section

```html
<main>
```
Defines the main content of a document

```html
<mark>
```
Defines marked/highlighted text

```html
<menuitem>
```
Defines a command/menu item that the user can invoke from a popup menu

```html
<meter>
```
Defines a scalar measurement within a known range (a gauge)

```html
<nav>
```
Defines navigation links

```html
<progress>
```
Represents the progress of a task

```html
<rp>
```
Defines what to show in browsers that do not support ruby annotations

```html
<rt>
```
Defines an explanation/pronunciation of characters (for East Asian typography)

```html
<ruby>
```
Defines a ruby annotation (for East Asian typography)

```html
<section>
```
Defines a section in a document

```html
<summary>
```
Defines a visible heading for a `<details>` element

```html
<time>
```
Defines a date/time

```html
<wbr>
```
Defines a possible line-break

Sample: HTML5

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Title of the document</title>
  </head>

  <body>
    <header>
    <nav></nav>
    </header>
    <main>
      <section>
        <article></article>
      </section>
      <aside></aside>
    </main>
    <footer></footer>
  </body>
</html>
```

### Custom HTML Elements
You can also add new elements to an HTML page with a browser trick. 
with the help of javascript.

```html
<!DOCTYPE html>
<html>
<head>
  <script>document.createElement("customElement")</script>
</head>
<body>

<h1>A Heading</h1>
<customElement>My custom Element</customElement>

</body>
</html>
```

### New Form Elements

```html
<datalist>
```
Specifies a list of pre-defined options for input controls
```html

<keygen>
```
Defines a key-pair generator field (for forms)

```html
<output>
```
Defines the result of a calculation

### HTML Graphics

```html
<canvas>
```

The HTML `<canvas>` element is used to draw graphics on a web page.

The graphic to the left is created with `<canvas>`. It shows four elements: a red rectangle, a gradient rectangle, a multicolor rectangle, and a multicolor text.

Sample:
```html
<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
Your browser does not support the HTML5 canvas tag.
</canvas>
```

```html
<svg>
```

The HTML `<svg>` element is a container for SVG graphics.

SVG has several methods for drawing paths, boxes, circles, text, and graphic images.


### What is SVG?

* SVG stands for Scalable Vector Graphics
* SVG is used to define graphics for the Web
* SVG is a W3C recommendation

Sample:

```html
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>
```

### HTML Attributes

Attributes provide additional information about HTML elements.

#### HTML Attributes

* All HTML elements can have attributes
* Attributes provide additional information about an element
* Attributes are always specified in the start tag
* Attributes usually come in name/value pairs like: name="value"

| Attribute       | Description                                                                                               |
|-----------------|-----------------------------------------------------------------------------------------------------------|
| accesskey       | Specifies a shortcut key to activate/focus an element                                                     |
| class           | Specifies one or more classnames for an element (refers to a class in a style sheet)                      |
| contenteditable | Specifies whether the content of an element is editable or not                                            |
| contextmenu     | Specifies a context menu for an element. The context menu appears when a user right-clicks on the element |
| data-*          | Used to store custom data private to the page or application                                              |
| dir             | Specifies the text direction for the content in an element                                                |
| draggable       | Specifies whether an element is draggable or not                                                          |
| dropzone        | Specifies whether the dragged data is copied, moved, or linked, when dropped                              |
| hidden          | Specifies that an element is not yet, or is no longer, relevant                                           |
| id              | Specifies a unique id for an element                                                                      |
| lang            | Specifies the language of the element's content                                                           |
| spellcheck      | Specifies whether the element is to have its spelling and grammar checked or not                          |
| style           | Specifies an inline CSS style for an element                                                              |
| tabindex        | Specifies the tabbing order of an element                                                                 |
| title           | Specifies extra information about an element                                                              |
| translate       | Specifies whether the content of an element should be translated or not                                   |
