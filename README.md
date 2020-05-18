<p align="center">
<img src="https://raw.githubusercontent.com/thecodrr/codeblock.css/master/assets/preview1.png" width="700">
</p>

<h1 align="center"><code>codeblock.css</code></h1>
<h3 align="center">Make your code blocks pretty again. Without all the bloat.</h3>
<p align="center">
  <a href="https://www.npmjs.com/package/codeblock.css"><img src="https://img.shields.io/npm/v/codeblock.css?style=for-the-badge"/></a>
  <a href="https://www.npmjs.com/package/codeblock.css"><img src="https://img.shields.io/npm/dt/codeblock.css?style=for-the-badge"/></a>
  <a href="https://www.npmjs.com/package/codeblock.css"><img src="https://img.shields.io/bundlephobia/minzip/codeblock.css?style=for-the-badge"/></a>
  <a href="./LICENSE"><img src="https://img.shields.io/github/license/thecodrr/codeblock.css?style=for-the-badge"/></a>
</p>
</p>

## Features:

**🕺 Extremely Lightweight:** `codeblock.css` is only 263 bytes big. Yep, only 263.

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
<div class="code">
  <span class="lang">html</span>
  <pre>
    &lt;!-- your code here --&gt;
  </pre>
</div>
```

You will get something like this:

<img src="https://raw.githubusercontent.com/thecodrr/codeblock.css/master/assets/preview2.png" width="700">

If you'd like to add a title to the code block, you'll have to do this:

```html
<div class="code">
  <div class="info">
    <span class="title">example 1</span>
    <span class="lang">html</span>
  </div>
  <pre>
    &lt;div class=&quot;code&quot;&gt;
      &lt;div class=&quot;info&quot;&gt;
        &lt;span class=&quot;title&quot;&gt;example 1&lt;/span&gt;
        &lt;span class=&quot;lang&quot;&gt;html&lt;/span&gt;
      &lt;/div&gt;
      &lt;pre&gt;
        &lt;!-- your code here --&gt;
      &lt;/pre&gt;
    &lt;/div&gt;
  </pre>
</div>
```

Which will look like this:

<img src="https://raw.githubusercontent.com/thecodrr/codeblock.css/master/assets/preview1.png" width="700">

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
