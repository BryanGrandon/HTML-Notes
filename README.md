# HTML Notes

HTML stands for HyperText Markup Language. It is used on the frontend and gives the structure to the webpage which you can style using CSS and make interactive using JavaScript.

## Table of content

- [HTML document structure](#html-document-structure)
- [Header labels](#header-labels)
  - [Title](#title)
  - [Metadata](#metadata)
  - [Link](#link)
- [Grouping labels](#grouping-labels)
- [Multimedia labels](#multimedia-labels)
  - [Image](#image)
  - [Video](#video)
  - [Audio](#audio)
- [Text labels](#text-labels)
- [Semantic](#semantic-labels)
- [Table label](#table-label)
- [Form label](#form-label)
- [Form validations](#form-validations)
- [Scripting label](#scripting-label)
- [Interactive labels](#interactive-labels)
  - [Details](#details)
  - [Dialog](#dialog)

## HTML document structure

```HTML
<!DOCTYPE html>
<!-- Tells the browser that the document is in HTML5  -->
<html lang="en">
  <!-- Represents the root of an HTML document -->
  <head>
  <!-- For information about the document -->
    <title>Web site title</title>
    <!-- For set the title of the website  -->
  </head>
  <body>
  <!-- To set the content that the user will see  -->
  </body>
</html>
```

[⬆️ Back to top ⬆️](#html-notes)

## Header labels

The **head** tag is responsible for containing HTML metadata tags (information about the document), as well as for establishing relationships with other documents.

### Title

The title tag is used to indicate the title of our document. It is a mandatory tag that must appear in an HTML document.

- It will determine the title of the browser window or tab.

- If the page is indexed in Google, it is very likely to use that title for the search engine result.

- It is an identifying title that can be used by bots or automatic systems that read the page.

### [Metadata](/code/metadata.html)

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

### Link

The link tag is used to establish relationships with other documents, links or files.

```HTML
<head>
  <link rel="icon" href="image.png" />
  <!-- Tab Website icon (img, links) -->

  <link rel="stylesheet" href="style.css" />
  <!-- Style of a CSS document -->
</head>
```

[⬆️ Back to top ⬆️](#html-notes)

## [Grouping labels](/code/grouping-labels.html)

Grouping tags can be divided into two main groups:

- Tags that contain text fragments (give meaning or context to those fragments).

- Tags that group other tags (they contain and group various information).

| Label          | Description                                              |
| -------------- | -------------------------------------------------------- |
| `<p>`          | Define a text paragraph.                                 |
| `<main>`       | Container to enclose the main part of the page.          |
| `<div>`        | Layer or division used to group several HTML tags.       |
| `<hr>`         | Indicates a thematic separation of the text.             |
| `<ol>`         | Creates a order list.                                    |
| `<ul>`         | Create an unordered list.                                |
| `<li>`         | Item from a order or unordered list.                     |
| `<pre>`        | Sets a preformatted text.                                |
| `<blockquote>` | Groups information and characteristics of a appointment. |
| `<dl>`         | Create a list of definitions.                            |
| `<dt>`         | Sets the term of a definition.                           |
| `<dd>`         | Sets the description of a term of a definition.          |
| `<figure>`     | Groups a visual element in a figure or illustration.     |
| `<figcaption>` | Sets a caption to a figure or illustration.              |

[⬆️ Back to top ⬆️](#html-notes)

## Multimedia labels

Display multimedia content on the website

### Image

Images are very important to make our page look good and pleasant or help to show and exemplify what we write in it.

```HTML
<img src="nameImage-URL" alt="Text describing the image" />
```

There are certain attributes that have to do with the performance when loading images and through which we can adjust the way in which the images in the `<img>` tags are processed and downloaded.

| Attribute     | Description                                                                                   |
| ------------- | --------------------------------------------------------------------------------------------- |
| loading       | Indicates whether the browser should download the image immediately or postpone the download. |
| decoding      | Indicates how and when the browser should process the images to display them.                 |
| fetchpriority | Indicates the priority to be given to downloading the image resource.                         |

### Video

Display video file on our website.

```HTML
<video src="video.mp4" controls></video>
```

| Control attributes | Description                                                |
| ------------------ | ---------------------------------------------------------- |
| autoplay           | It starts playing the video automatically.                 |
| loop               | Restart the video when it finishes playing (looping).      |
| muted              | Sets the video to play with muted sound.                   |
| controls           | Displays the playback controls (not displayed by default). |
| playsinline        | Plays the video online, i.e. in your playback area.        |

### Audio

Display audio file on our website.

```HTML
<audio src="audio.mp3" controls></audio>
```

| Control attributes | Description                                                 |
| ------------------ | ----------------------------------------------------------- |
| loop               | Sets the audio to repeat at the end (loop mode).            |
| muted              | Sets the audio to mute (muted).                             |
| controls           | Displays the playback controls (not displayed by default).  |
| autoplay           | Starts playing the audio automatically when the page loads. |

## [Text labels](/code/text-labels.html)

The main thing is to understand that it is not done for mere visual intention, but because it is intended to give it a semantic meaning.

| Tags       | Its function                  |
| ---------- | ----------------------------- |
| `<a>`      | Create a link.                |
| `<strong>` | Important text.               |
| `<em>`     | Emphasized text.              |
| `<mark>`   | Marked text.                  |
| `<span>`   | Text excerpt.                 |
| `<sup>`    | Superscript.                  |
| `<sub>`    | Subindex                      |
| `<cite>`   | Author name, work, book, etc. |
| `<code>`   | Code fragment.                |

## [Semantic labels](/code/semantic.html)

We prepare our HTML document so that any browser, search engine robot, application or computer system will be able to read the HTML document and know perfectly the nature of the content of that section.

| Tags        | Its function                                 |
| ----------- | -------------------------------------------- |
| `<h1>`      | Header level 1                               |
| `<h2>`      | Header level 2                               |
| `<h3>`      | Header level 3                               |
| `<h4>`      | Header level 4                               |
| `<h5>`      | Header level 5                               |
| `<h6>`      | Header level 6                               |
| `<header>`  | Header on a wed site or a section            |
| `<nav>`     | Represents a navigation                      |
| `<section>` | Represents a section of generic content      |
| `<article>` | Self explanatory section                     |
| `<footer>`  | footer of a website or a section             |
| `<aside>`   | represents supplemental or secondary content |
| `<address>` | represents a contact information             |

## [Table label](/code/table.html)

Tables have been included in HTML since its earliest versions and are a fantastic way to display data clearly.

```HTML
<!-- Create table -->
<table>
  <!-- Table title -->
  <caption>Title for table</caption>
  <!-- Table header -->
  <thead>
    <!-- Table row -->
    <tr>
      <!-- Table head -->
      <th>Element</th>
    </tr>
  </thead>
  <!-- Table body -->
  <tbody>
    <tr>
      <!-- Table data -->
      <td>Element</td>
    </tr>
  </tbody>
  <!-- Table footer -->
  <tfoot>
    <tr>
      <td>Element</td>
    </tr>
  </tfoot>
</table>
```

## [Form label](/code/form-label.html)

A form is known as a mechanism for sending information by the user, through visual fields in a simple and intuitive way.

```HTML
<form action="" method="">
  <!-- Short text information -->
  <input type="text" name="username" />

  <!-- Long text information -->
  <textarea name="" id="" cols="30" rows="10"></textarea>

  <!-- send the form -->
  <input type="submit" value="Submit" />
</form>
```

## [Form validations](/code/form-validations.html)

HTML5 introduces new form attribute that allow form validation to be performed directly in HTML5, without the need for JavaScript.

| attribute | Can act on...     | description                                                               |
| --------- | ----------------- | ------------------------------------------------------------------------- |
| maxlength | Text fields       | Does not allow to write texts longer than a certain number of characters. |
| minlength | Text fields       | Sets the minimum text length required.                                    |
| min       | Numeric fields    | Establishes the minimum number allowed.                                   |
| max       | Numeric fields    | Establishes the maximum number allowed.                                   |
| required  | Fields in general | Required field. It must be filled in to send the form.                    |
| disable   | Fields in general | File deactivated. Cannot be modified. Not sent.                           |
| readonly  | Fields in general | Read-only field. Cannot be modified. It is send.                          |

## Scripting label

The `<script>` tag allows us to indicate in our HTML that we are going to load a script (a text file with JavaScript code) and make it run on the current web document.

- Inline script: The JS code is included in the HTML, within the tag itself.

  ```HTML
  <script>
      alert("Hello world")
  </script>
  ```

- External script: The JS code is included in the JavaScript file linked in the src attribute.

  ```HTMl
  <script src="file.js "></script>
  ```

| attributes | Its function                                                                                                                                                   |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Async      | Indicates that the script should be downloaded asynchronously and then executed as soon as it becomes available.                                               |
| Defer      | Indicates that the script should be downloaded asynchronously and then executed once it has been fully downloaded and the HTML document has been fully parsed. |

```HTML
<head>
    <script src="script.js" async></script>
    <script src="script.js" defer></script>
</head>
```

## [Interactive labels](/code/interactive.html)

### Details

The `<details>` tag gives us the possibility to create a drop-down element, which the user can expand or collapse to see more information that will be hidden.

```HTML
<details>
  <summary>Dropdown Title</summary>
  <p>More Info</p>
  <img src="" alt="" />
</details>
```

### Dialog

As of HTML5.1, a `<dialog>` tag is incorporated by means of which we can build our own customized dialog windows.

```HTML
<dialog id="dialog-window">
  <p>Hi, I am a message</p>
  <img src="" alt="" />
  <button id="close" onclick="document.getElementById('dialog-window').close()">
    Close
  </button>
</dialog>
<button id="show" onclick="document.getElementById('dialog-window').show()">
  Show
</button>
```
