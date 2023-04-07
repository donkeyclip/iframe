# Using Donkeyclip with an Iframe

To embed a Donkeyclip video player on your website using an iframe, simply include the following HTML code and replace the `src` attribute with the URL of the Donkeyclip player hosted on your server or CDN:

```html
<iframe
  src="<your-donkeyclip-url>?controls"
  width="640"
  height="360"
  frameborder="0"
  allow="autoplay; fullscreen"
  allowfullscreen
></iframe>
```

# Available query params

- `scaleToFit` (optional): A boolean or string value that, when set to `true`, scales the clip to fit the player dimensions.
- `mcVersion` (optional): A string specifying the version of the MotionComposer library to use.
- `playerVersion` (optional): A string specifying the version of the Donkeyclip Player library to use.
- `theme` (optional): A `PlayerTheme` that sets the player's theme. Read more [here](https://github.com/donkeyclip/motorcortex-player)
- `initParams` (optional): An stringified object containing `DefinitionParams` for initializing the clip.
- `visible` (optional): A string value `"always"` indicating that the player should always be visible.
- `ms` (optional): A number or string value representing the millisecond at which the clip should start playing.
- `volume` (optional): A number or string value representing the volume level of the clip.
- `speed` (optional): A number or string value representing the playback speed of the clip.
- `backgroundColor` (optional): A string value representing the background color of the player.
- `spinnerColor` (optional): A string value representing the color of the loading spinner.
