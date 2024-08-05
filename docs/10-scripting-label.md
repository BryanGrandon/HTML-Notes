# Scripting label

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
