<h1 align="center">
  CSS 🦚
</h1>

<p align="center">
  <strong>~400 bytes of CSS to look great nearly everywhere</strong>
</p>

Inspired by [this gist](https://gist.github.com/JoeyBurzynski/617fb6201335779f8424ad9528b72c41), here are my personal ~400 copy-&-pasteable bytes of CSS to make pages look great nearly everywhere, and box-sizing behave well:

```css
body {
  font-family: ui-sans, sans-serif;
  font-size: 1.05em;
  line-height: 1.5em;
  margin: auto;
  max-width: 70ch;
  padding: 4rem 1rem;
  > :first-child { margin-top: 0; }
  > :last-child { margin-bottom: 0; }
}
h1, h2, h3, h4, h5, h6 {
  margin: 2em 0 1rem;
}
article, blockquote, header, footer, ol, ul, hr, p, pre {
  margin: 1.5em 0;
}
*, ::before, ::after {
  box-sizing: border-box;
}
```
