# tiny-spinner
Very simple and tiny spinner built with CSS only. 

## Configuration

Use the CSS variables! By default these are the values:
```CSS
:root {
  --tiny-spinner-color: #000;
  --tiny-spinner-duration: 1s;
  --tiny-spinner-position: fixed;
  --tiny-spinner-size: 2rem;
  --tiny-spinner-thickness: 0.25rem;
}
```

If you want to override the values, just use more specific CSS eg with a container, `body` or the spinner itself, eg
```CSS
.tiny-spinner {
  --tiny-spinner-color: coral;
  --tiny-spinner-duration: 3s;
  --tiny-spinner-size: 12rem;
  --tiny-spinner-thickness: 1rem;
}
```

### Position: `fixed` or `absolute`
By default the spinner is `position:fixed` so it is centered on the window. You can set it to `absolute` so that it sits within a container:
```CSS
.tiny-spinner {
  --tiny-spinner-position: absolute;
}
```
**Be sure to set the container to be `position: relative`!**


## Example
Open [the demo](//buzinas.github.io/tiny-spinner) and see how simple and beautiful it is.

## Browser support
IE10+ and all the modern browsers

## License
[MIT](LICENSE)
