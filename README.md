<p align="center">
<img src="https://raw.githubusercontent.com/thecodrr/codeblock.css/master/assets/preview1.png" width="700">
</p>

<h1 align="center"><code>codeblock.css</code></h1>
<h3 align="center">Make your code blocks pretty again. Without all the bloat.</h3>

## Features:

**🕺 Extremely Lightweight:** `codeblock.css` is only 400 bytes big. Yep, only 400.

**🌐 Works Everywhere:** `codeblock.css` uses nothing except pure-CSS that works everywhere on every browser.

**📱 Responsive:** `codeblock.css` works even on mobiles and small screens.

**🎨 Themeable:** Theme it however you want. Change the font, the background, the foreground, the title...anything.

**😐 Simple:** `codeblock.css` does not make you learn anything new. All you have to do is assign ids to HTML elements. That's it.

**⚙️ So simple, even GitHub can handle it (if it supported inline styles :D).**

## Installation:

Simply add this in your `<head>`:

```html
<link rel="stylesheet" href="https://unpkg.com/codeblock.css" />
```

## Usage:

The most simplest way of using `codeblock.css` is:

```html
<div id="code">
  <span id="lang">javascript</span>
  <pre>
    <!-- your code here -->
  </pre>
</div>
```

You will get something like this:

<img src="https://raw.githubusercontent.com/thecodrr/codeblock.css/master/assets/preview2.png" width="700">

## Theming:

By default, `codeblock.css` uses these variables for theming:

```css
--code-bg: #ededed;
--code-fg: #000;
--code-title-fg: #7b7b7b;
--code-lang-fg: #6b6b6b;
--code-font: monospace;
```

You can modify these to your heart's content to get the desired effect.

There are also some themes in the `/themes` directory which you can directly link to by adding this to your `<head>`:

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/codeblock.css/themes/<theme-name-here>.css"
/>
```

## LICENSE

```
Copyright (c) 2020 Abdullah Atta under MIT.
```
