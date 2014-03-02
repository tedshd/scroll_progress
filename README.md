scroll_progress
===============

Show a progress bar about page scroll position.

[Develop note](http://tedshd.logdown.com/posts/183010-javascript-scroll-progress)

### Usage

Need embed `scroll_progress.js` and `scroll_progress.css`

Call a function

```javascript
ScrollProgress();
```

It can show default progress bar on the top.

You also can customize progress position thick and color.

Add a object as a parameter in `ScrollProgress()`

#### parameter

* position [string]

  * Define progress bar position

  * `left`, `right`, `top`, `bottom`, default is `top`.

* thick [number]

  * Show progress bar thickness, default is `5`.

* color [string]

  * Show progress bar color, default is `#ff0000`.

Example

```javascript
var setting = {
    position: 'left',
    thick: 10,
    color: '#ff8800'
}
ScrollProgress(setting);

// or
var setting = {
    color: '#ff8800'
}
ScrollProgress(setting);
```
