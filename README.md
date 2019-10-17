# postcss-wrap-selector

[PostCSS](https://github.com/postcss/postcss) plugin for adding a parent selector to all rules in a css file.

## Options

There are two interesting configs about this plugins. The `selector` option takes a string value that should be placed at the beginning of each selector, including selector lists separated by commas. The `skipRootSelector` option takes a string or an array, if a selector starts with specified root selector, this selector will be skipped.

```json
{
  "selector": ".parent",
  "skipRootSelector": [".lightblue", ".black"]
}
```
