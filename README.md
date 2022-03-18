## JS Title Animation

```html
<script src="https://tobyck.surge.sh/modules/title-animation/script.js"></script>
```
### Functions
* `element.setText(text, fadeInTime, delay)` - Set the text of an element to the text provided in a way that makes in animatable with the following functions.
* `element.clearText(delay)` - Removes the text from an element.
* `element.animateText(YpositionToAnimateTo, animationTime, delay)` - Animates the element to the Y position provided (e.g `"60vh"`).
All times are in milliseconds, and default to 0. It is also important to note that delay times are asynchronous.

### Example
<img src="https://title-animation.surge.sh/helloworld.gif" alt="'Hello World!' being animated up and down like a wave" style="height: 400px;">
