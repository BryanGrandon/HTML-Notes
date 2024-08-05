# Header labels

The **head** tag is responsible for containing HTML metadata tags (information about the document), as well as for establishing relationships with other documents.

## Title

The title tag is used to indicate the title of our document. It is a mandatory tag that must appear in an HTML document.

- It will determine the title of the browser window or tab.
- If the page is indexed in Google, it is very likely to use that title for the search engine result.
- It is an identifying title that can be used by bots or automatic systems that read the page.

## [Metadata](/code/metadata.html)

Metadata are HTML elements that are placed in the header to establish the information of our web page. This allows search engines to show the user our website if the search is related to our website.

```HTML
<head>
  <meta charset="UTF-8" />
  <!-- Character encoding System -->

  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- Responsive design for wed page -->

  <script src="javascript.js" defer></script>
  <!-- Functionality of the website of a JS document -->
</head>
```

## Link

The link tag is used to establish relationships with other documents, links or files.

```HTML
<head>
  <link rel="icon" href="image.png" />
  <!-- Tab Website icon (img, links) -->

  <link rel="stylesheet" href="style.css" />
  <!-- Style of a CSS document -->
</head>
```
