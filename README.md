# 👚 blouse.css

A lightweight mobile first CSS framework. No reset, no extra classes. Less than <strong>1Kb</strong> compressed plus 5.2 Kb for the icons.

**[See it live in Codepen](https://codepen.io/albo-ar/pen/YzQaWoK?editors=1000)**

## How to use

Add the following tags in the `<head>`

```html  
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/4lb0/blouse.css@latest/dist/blouse.css" crossorigin="anonymous">
```

## Documentation

### Menu

```html 
<nav role="navigation">
  <input type="checkbox" id="menu-toggle" aria-hidden="true" />
  <a href="/">My brand</a>
	<label for="menu-toggle" aria-hidden="true"></label>
  <ul>
    <li><a href="#">First link</a></li>
    <li><a href="#">Second link</a></li>
    <li><a href="#">Third link</a></li>
  </ul>
</nav>
```

### Forms

```html 
<button class="main">Primary button</button>
<button class="alt">Secondary button</button>
<p class="msg ok" hidden>Operation successful</p>
<p class="msg err" hidden>Operation error</p>
<p class="msg warn" hidden>Some warning</p>
<p class="msg info" hidden>Some info</p>

<!-- Alert is a pop up notification at the top of the page -->
<p class="alert ok" hidden aria-hidden="true">Saved ok!</p>
```

### Footer


```html 
<footer>
  <span>Some content</a>
  <span><a href="#">A link</a></span>
  <span>
    <i class="gh" aria-hidden="true" title="GitHub"></i>
  </span>
</footer>
```

### Utilities

```html 
<a class="btn" href="#">This is a button</a>
<a class="btn main" href="#">Main button</a>
<a class="btn alt" href="#">Alternative button</a>
<p class="text-center">This text is align in the center.</p>
<p class="mute">This text is muted.</p>    
<p class="mt-2">This text has a space on top.</p>
<p class="mt-4">This text has double space on top.</p>
```

### Icons

```html
Twitter: <i class="tw" aria-hidden="true" title="Twitter"></i>
Facebook: <i class="fb" aria-hidden="true" title="Facebook"></i>
GitHub: <i class="gh" aria-hidden="true" title="GitHub"></i>
LinkedIn: <i class="in" aria-hidden="true" title="LinkedIn"></i>
WhatsApp: <i class="wa" aria-hidden="true" title="WhatsApp"></i>
Telegram: <i class="tl" aria-hidden="true" title="Telegram"></i>
Youtube: <i class="yt" aria-hidden="true" title="Youtube"></i>
Instagram: <i class="ig" aria-hidden="true" title="Instagram"></i>
Twitch: <i class="ti" aria-hidden="true" title="Twitch"></i>
```
