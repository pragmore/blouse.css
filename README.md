# A minimal CSS framework

Another mobile first CSS framework. No reset, no extra classes. Try to use as much HTML5 and default styles as you can.

**[See it live in Codepen](https://codepen.io/albo-ar/pen/YzQaWoK?editors=1000)**

## How to use

Add the following link in the `<head>`

```html  
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/pragmore/css@latest/dist/framework.css" crossorigin="anonymous">
```

## Documentation

### Forms

```html 
<button class="primary">Primary button</button>
<button class="alt">Secondary button</button>
<p class="msg ok" hidden>Operation successful</p>
<p class="msg err" hidden>Operation error</p>
<p class="msg warn" hidden>Some warning</p>
<p class="msg info" hidden>Some info</p>

<!-- Alert is a pop up notification at the top of the page -->
<p class="alert ok" hidden>Saved ok!</p>
```

### Utilities

```html 
<a class="btn" href="#">This is a button</a>
<p class="center">This text is align in the center.</p>    
<p class="muted">This text is muted.</p>    
<p class="space">This text has a space on top.</p>    
<p class="more-space">This text has more space on top.</p>
<p class="hide">Hide this text</p>
```
