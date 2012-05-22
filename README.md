# Xevent

Xevent is a micro library (~1KB uncompressed) for working with events across all browsers. Xevent is compatiable with IE 7+, FF 1+, Chrome 1+, Opera 7+, and Safari 1+.

## API

### xevent.attachEventHandler(obj, type, func)
* `obj`: The DOM element the event will be attached to.
* `type`: A string representing the event type to listen for.
* `func`: The function to call when the event occurs. An event object will be passed to it.

### xevent.removeEventHandler(obj, type, func)
* `obj`: The DOM element the event listener is to be removed from.
* `type`: A string representing the event type being removed. 
* `func`: The function to be removed. 

### xevent.preventDefault(event)
* `event`: The event object to prevent the default browser action of.

### xevent.stopPropagation(event)
* `event`: The event object to stop the propagation of. 
