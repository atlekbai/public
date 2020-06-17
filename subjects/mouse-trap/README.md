## Mouse trap

### Instructions

Develop a trap to capture the elements when the mouse is getting too close to the center of the page!

- Create a function `createCircle`: make it fire on every click on the page, and create a `div` at the position of the mouse on the screen, setting its `background` to `white` and its class to `circle`

- Create a function `moveCircle`: make it fire when the mouse moves, and get the last circle created and makes it move along with the mouse

- Set a box in the center of the page ; when a circle is inside that box, it has to be purple ; once a circle enters the box, it is trapped inside and cannot go out of it anymore.

### Notions

- [`addEventListener()`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener): `click`, `mousemove`
- [`removeEventListener()`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/removeEventListener)
- [Mouse event](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent/MouseEvent): [`click`](https://developer.mozilla.org/en-US/docs/Web/API/Element/click_event), [`mousemove`](https://developer.mozilla.org/en-US/docs/Web/API/Element/mousemove_event) / [`clientX`](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent/clientX), [`clientY`](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent/clientY)
- [`getBoundingClientRect()`](https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect)

### Provided files

- Use the HTML file [index.html](/public/subjects/mouse-trap/index.html), which includes:

  - the JS script which will allow to run your code
  - some CSS pre-styled classes: feel free to use those as they are, or modify them

### Expected result

You can see an example of the expected result [here](https://youtu.be/qF843P-V2Yw)