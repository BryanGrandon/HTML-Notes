# HTML Notes

HTML stands for HyperText Markup Language. It is used on the frontend and gives the structure to the webpage which you can style using CSS and make interactive using JavaScript.

- [Introduction](#introduction)
- [Basic Structure](#basic-structure)
- [Metadata](#metadata)

## _Introduction_

This project is to have a record of what i have learned about HTML.

**Extensions to use:** [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## _Basic Structure_

The [Basic Structure](/code/basic-structure.html) of a web page consists of `<html>`, `<head>` and `<body>` tags.

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

## _Metadata_

[Metadata](/code/metadata.html) are HTML elements that are used by search engines to define the main information of our web site, since meta data shows information about the web page that contains them.
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
