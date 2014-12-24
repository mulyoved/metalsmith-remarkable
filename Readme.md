
# metalsmith-remarkable

  A Metalsmith plugin to convert markdown files using remarkable.
  (Copy & Paste from https://github.com/segmentio/metalsmith-markdown)

## Installation

    $ npm install metalsmith-remarkable

## CLI Usage

  Install via npm and then add the `metalsmith-markdown` key to your `metalsmith.json` plugins with any [Marked](https://github.com/chjj/marked) options you want, like so:

```json
{
  "plugins": {
    "metalsmith-remarkable": {
    }
  }
}
```

## Javascript Usage

  Pass `options` to the markdown plugin and pass it to Metalsmith with the `use` method:

```js
var markdown = require('metalsmith-remarkable');

metalsmith.use(markdown({
}));
```

## License

  MIT