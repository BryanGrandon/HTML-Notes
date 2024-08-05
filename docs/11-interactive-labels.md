# [Interactive labels](/code/interactive.html)

## Details

The `<details>` tag gives us the possibility to create a drop-down element, which the user can expand or collapse to see more information that will be hidden.

```HTML
<details>
  <summary>Dropdown Title</summary>
  <p>More Info</p>
  <img src="" alt="" />
</details>
```

## Dialog

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
