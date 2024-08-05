# Multimedia labels

Display multimedia content on the website

## Image

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

## Video

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

## Audio

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
