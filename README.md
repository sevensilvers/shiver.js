# shiver.js

| Option     | Default | Description                                                                                |
|------------|---------|--------------------------------------------------------------------------------------------|
| x          | 2       | Set the horizontal shiver range (pixels)                                                   |
| y          | 2       | Set the vertical shiver range (pixels)                                                     |
| rotation   | 1       | Set the rotation range (degrees)                                                           |
| speed      | 15      | Set the speed/frequency in milliseconds between shiver movements (lower number = faster)   |
| opacity    | false   | Activate opacity flickering while shivering                                                |
| opacityMin | 5       | When the opacity option is set to true, this controls the minimum opacity while flickering |

```
// Initialize Shiver
var el = new Shiver(Element, options);

// Start shiver on element
el.startShiver();

// Stop shiver on element
el.stopShiver();
```