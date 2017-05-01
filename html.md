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
