# HTML Notes

HTML stands for HyperText Markup Language. It is used on the frontend and gives the structure to the webpage which you can style using CSS and make interactive using JavaScript.

- [Introduction](#introduction)
- [Basic Structure](#basic-structure)
- [Metadata](#metadata)
- [Grouping Labels](#grouping-labels)
- [Text Labels](#text-labels)

## _Introduction_

This project is to have a record of what i have learned about HTML.

**Extensions to use:** [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## _[Basic Structure](/code/basic-structure.html)_

The Basic Structure of a web page consists of `<html>`, `<head>` and `<body>` tags.

```HTML
<!DOCTYPE html>
<!-- Tells the browser that the document is in HTML5 -->
<html lang="en">
  <!-- Represents the root of an HTML document -->
  <head>
    <!-- For information about the document -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Web site title</title>
  </head>
  <body>
    <!-- For content -->
  </body>
</html>
```

## _[Metadata](/code/metadata.html)_

Metadata are HTML elements that are used by search engines to define the main information of our web site, since meta data shows information about the web page that contains them.
<br />
These meta elements will be found in the **head** of the web code.

```HTML
<head>
    <meta charset="UTF-8" />
    <!-- Character encoding System -->

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Responsive design for wed page -->

    <meta name="description" content="The main function of the website" />
    <!-- Website description for each HTML document -->

    <meta name="keywords" content="html" />
    <!-- List of keywords separated by commas -->

    <meta name="author" content="Bryan" />
    <!-- Indicates the name of the author of the page. -->

    <meta name="application-name" content="Dev" />
    <!-- name of the web application. if it is a webapp. -->

    <meta name="generator" content="VSCode" />
    <!-- Indicates the software used to create the web page. -->

    <meta name="theme-color" content="#1e7bbf" />
    <!-- Hexadecimal color of the navigation bar. -->

    <link rel="icon" href="image.png" />
    <!-- Tab Website icon (img, links) -->

    <link rel="stylesheet" href="style.css" />
    <!-- Style of a CSS document -->
  </head>
```

## _[Grouping Labels](/code/grouping-labels.html)_

Grouping labels are labels used to group and associate related information.

```HTML
<div></div>
<!-- Layer or division used to group several HTML tags. -->

<p>Define a text paragraph</p>

<main></main>
<!-- Container to enclose the main part of the page. -->

<hr />
<!-- Indicates a thematic separation of the text. -->

<ol></ol>
<!-- Creates a numbered list (with order). -->

<ul></ul>
<!-- Create a list where the order does not matter. -->

<li>Contains one of the items from a numbered or unnumbered list.</li>

<pre>Sets a preformatted text.</pre>

<blockquote></blockquote>
<!-- Groups information and characteristics of a appointment. -->

<dl></dl>
<!-- Create a list of definitions. -->

<dt>Sets the term of a definition.</dt>

<dd>Sets the description of a term of a definition.</dd>

<figure></figure>
<!-- Groups a visual element in a figure or illustration. -->

<figcaption>Sets a caption to a figure or illustration.</figcaption>
```

## _[Text Labels](/code/text-labes.html)_

The main thing is to understand that it is not done for mere visual intention, but because it is intended to give it a semantic meaning.

```HTML
<pre>
  <a href="" target="">Create a link.</a>

  <strong>Important text.</strong>

  <em>Emphasized text.</em>

  <mark>Marked text.</mark>

  <span>Text excerpt.</span>

  <span>24<sup>Superscript</sup></span>

  <span>26<sub>Subindex</sub></span>

  <cite>Author Name, work, book, etc</cite>

  <code>Code fragment</code>
</pre>
```
