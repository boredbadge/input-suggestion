# input-suggestion

[![](https://circleci.com/gh/1000ch/input-suggestion.svg?style=shield&circle-token=c2cd81d5e68b0c2429278a315f2c1249c0d09378)](https://circleci.com/gh/1000ch/input-suggestion)
[![NPM version](https://badge.fury.io/js/input-suggestion.svg)](http://badge.fury.io/js/input-suggestion)
[![Dependency Status](https://david-dm.org/1000ch/input-suggestion.svg)](https://david-dm.org/1000ch/input-suggestion)
[![devDependency Status](https://david-dm.org/1000ch/input-suggestion/dev-status.svg)](https://david-dm.org/1000ch/input-suggestion#info=devDependencies)

Show suggestions when you input.

![](demo.gif)

## Install

Using npm:

```sh
$ npm install input-suggestion
```

Using bower:

```sh
$ bower install input-suggestion
```

## Usage

```html
<textarea></textarea>
<script>
  var is = new InputSuggest('textarea');
  is.setSuggestions(['Apple', 'Apple Watch', 'Mac', 'iPad', 'iPhone', 'iPod', 'iPod Touch']);
</script>
```

## Customize popup

You can style popup with following HTML structure.

```html
<ul class="suggestion is-shown">
  <li class="suggestion__item is-selected">Item1 is selected</li>
  <li class="suggestion__item">Item2</li>
  <li class="suggestion__item">Item3</li>
</ul>
```

## License

MIT: http://1000ch.mit-license.org
