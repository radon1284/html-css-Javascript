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

**<!DOCTYPE>**

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
