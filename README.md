# MarkBB

MarkBB is a very lightweight Markdown and BBCode parser. It is written in JavaScript and can be used in any modern web browser.

## Usage

To use MarkBB, simply include the `markbb.min.js` file in your HTML document and call the `markbb` function with the Markdown or BBCode string as an argument.

```html
<script src="markbb.min.js"></script>
<script>
  var html = markbb("**Hello, world!**");
  document.body.innerHTML = html;
</script>
```

This will convert the Markdown string to HTML and insert it into the `body` element of the document.