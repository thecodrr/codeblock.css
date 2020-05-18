<h1 align="center">code.css</h1>
<h3 align="center">Make your code pretty again. Without all the bloat.</h3>

## Features:

**🕺 Extremely Lightweight:** `code.css` is only 400 bytes big. Yep, only 400.

**🌐 Works Everywhere:** `code.css` uses nothing except pure-CSS that works everywhere on every browser.

**📱 Responsive:** `code.css` works even on mobiles and small screens.

**🎨 Themeable:** Theme it however you want. Change the font, the background, the foreground, the title...anything.

**😐 Simple:** `code.css` does not make you learn anything new. All you have to do is assign ids to HTML elements. That's it.

**⚙️ So simple, even GitHub can handle it:**

<div style="display: flex; flex-direction: column;background-color: #383a59; padding: 20px; ">
   <div style="display: flex;
      justify-content: space-between;">
      <span style="font-family: monospace; color: #e3d2fa;">example 1</span>
      <span style="font-family: monospace; font-size: 12px; color: #e3d2fa;">html</span>
   </div>
   <pre style="color: #bd93f9; background: transparent; padding:0px; margin-bottom: 0px; max-width: 100%; overflow-x: auto;">
&lt;div id=&quot;code&quot;&gt;
   &lt;div id=&quot;info&quot;&gt;
      &lt;span id=&quot;title&quot;&gt;example 1&lt;/span&gt;
      &lt;span id=&quot;lang&quot;&gt;javascript&lt;/span&gt;
   &lt;/div&gt;
   &lt;pre&gt;
     &lt;!-- your code here --&gt;
   &lt;/pre&gt;
&lt;/div&gt;
</pre>

</div>

> _theme: dracula_

## Installation:

Simply add this in your `<head>`:

```html
<link rel="stylesheet" href="https://unpkg.com/code.css" />
```

## Usage:

The most simplest way of using `code.css` is:

```html
<div id="code">
  <span id="lang">javascript</span>
  <pre>
    <!-- your code here -->
  </pre>
</div>
```

You will get something like this:

<div style="display: flex; flex-direction: column;background-color: #383a59; padding: 20px; ">
    <span style="font-family: monospace; font-size: 12px; color: #e3d2fa; align-self: flex-end;">html</span>
   <pre style="color: #bd93f9; background: transparent; padding:0px; margin-bottom: 0px; max-width: 100%; overflow-x: auto;">
&lt;!-- your code here --&gt;
</pre>
</div>

## Theming:

By default, `code.css` uses these variables for theming:

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
  href="https://unpkg.com/code.css/themes/<theme-name-here>.css"
/>
```

## LICENSE

```
Copyright (c) 2020 Abdullah Atta under MIT.
```
