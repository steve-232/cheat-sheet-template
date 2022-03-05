# Cheat Sheet Template

HTML template for easily saving, grouping, sharing, and using any kind of commands and functions from different languages, tools, and plugins. The navigation menu is dynamically created during runtime.

Demo is [here](https://steve-232.github.io/cheat-sheet-template/).

## Usage

JS and CSS are inserted directly into the Page. Just update the HTML.

Enable copying of command by adding "copy-content" class to the "pre" tag.

```html
<pre class="copy-content"><code>plugin command <i>argument</i></code></pre>
```

<br />

Enable clearing of multiple white-spaces by adding "data-clear-white-space" attribute

```html
<pre class="copy-content" data-clear-white-space>
  <code>query {
    &nbsp;nameOfTheFunction {
      &nbsp;&nbsp;property_1
      &nbsp;&nbsp;property_2
      &nbsp;&nbsp;property_3
    &nbsp;}
    }
  </code>
</pre>
```

## License

[MIT license](http://www.opensource.org/licenses/MIT)
