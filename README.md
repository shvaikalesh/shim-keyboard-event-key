# shim-keyboard-event-key

`KeyboardEvent#key` shim for IE and Edge.

* [Edge bug report](https://developer.microsoft.com/en-us/microsoft-edge/platform/issues/8860571)
* [Can I use `key`?](http://caniuse.com/#feat=keyboardevent-key)
* [W3C: UI Events spec](https://www.w3.org/TR/uievents)
* [W3C: `key` values](https://www.w3.org/TR/uievents-key)

## Up and running

Get the package from [npm](https://www.npmjs.com/package/shim-keyboard-event-key):

`npm install shim-keyboard-event-key --save`

Simply require the module:

`import "shim-keyboard-event-key"`

## Example

```js
switch (event.key) {
  case "ArrowLeft":
  case "PageUp":
    player.prev()
    break

  case "ArrowRight":
  case "PageDown":
    player.next()
    break
}
```
