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

