# 👚 blouse.css

This responsive tiny framework allows you to focus on the content. Don't waste time with design until your app is working. Less than **1Kb** compressed\* and **4.4Kb** for the icons.

![CSS size in bytes](https://img.shields.io/github/size/pragmore/blouse.css/dist/default.css?label=uncompressed%20size)
![Icons font size in bytes](https://img.shields.io/github/size/pragmore/blouse.css/dist/bi.woff2?label=icons%20size)

## Features

* Semantic HTML ✅
* Mobile first ✅
* Dark mode ✅
* Lightweight, minimal footprint ✅
* No JavaScript \*\* ✅
* Icons for social networks ✅

[See it live](https://pragmore.com/blouse/)

\* When minified and compressed with the widely supported brotli algorithm.

\*\* The demo menu uses JS to close it when a link is clicked.
It is only necessary on anchors, not when they're linked to other pages.

## How to use

Copy the following code or download the [starter template](dist/starter-template.html)

```html
<!doctype html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="dist/blouse.css">
</head>
<body>
  <nav><!-- Optional menu --></nav>
  <main>
    <!-- Put your content here! -->
  </main>
  <footer><!-- Optional footer --></footer>
</body>
</html>
```

## Documentation

Use as much semantic HTML as possible, see the [demo](https://pragmore.github.io/blouse.css/) for reference.

### Utilities

We use the class names from [Tailwind](https://tailwindcss.com/) in case you later want to migrate to it.

```html
<p class="text-center">This text is align in the center.</p>
<p class="text-lg">This text is big.</p>
<p class="mute">This text is muted.</p>
<p class="mt-2">This text has a space on top.</p>
<p class="mt-4">This text has double space on top.</p>
```

### Menu

```html 
<nav>
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

### Forms and messages

```html 
<a class="btn" href="#">Regular button</a>
<a class="btn main" href="#">Main button</a>
<a class="btn alt" href="#">Alternative button</a>

<input type="submit" value="Regular button" />
<input type="submit" class="main" value="Main button" />
<input type="submit" class="alt" value="Alternative button" />

<button>Regular button</button>
<button class="main">Main button</button>
<button class="alt">Alternative button</button>

<p class="msg ok">Ok message</p>
<p class="msg err">Error message</p>
<p class="msg info">Info message</p>
<p class="msg warn">Warning message</p>
```

Alerts are popup notification showed at the top (over the menu). The close button needs to be implemented with JavaScript. Use `role="alert"` when hidden to make it accesible.

```html 
<p class="msg alert ok">This is an alert ok.</p>

<p class="msg alert err" hidden role="alert">
  This is an alert error. 
  <b title="Close" aria-label="Close the alert." onclick="this.parentElement.hidden=true">✕</b>
</p>
```

### Icons

Use emojis for most of the icons you need, like 🖨️, ⚙️ or 📞 But for social networks we needs icons, here you have the most used: 

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

## Themes

The framework has different themes.

* Default
* Warm
* Cool
* Sea
* Balloon
* Solid
* Party
* Idea

### CDN 

Use Pragmore's cdn cdn.pragmore.com/**version**/**theme**/blouse.css?font=**font-family**&family=**generic-family**&size=**font-size**. The default font family is Helvetica, Arial, the default generic family is sans-serif and the default font size is 14pt. Example for the release in the 2.0 version with the warm theme and the Roboto Mono font:

```html
<link rel="stylesheet" href="https://cdn.pragmore.com/2.0/warm/blouse.css?font=Roboto+Mono&family=monospace&size=16pt" crossorigin="anonymous">
```

-------------------

Made with ❤️, by [Pragmore](https://github.com/pragmore) 

