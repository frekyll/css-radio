# css-radio
> Friendly CSS radio button

[![Build Status](https://travis-ci.org/frekyll/css-radio.svg?branch=master)](https://travis-ci.org/frekyll/css-radio)

This is inspired by [wtf-forms](https://github.com/mdo/wtf-forms). I often find myself copying this source, so I made a package.

## Features

- Create a larger hit area for checking the control
- Replace the default `<input>` with a semantic wrapper
- Trigger the state of `<input>` automatically

## Example

```html
<label class="radio">
	<input id="example" name="radio" type="radio">
	<span class="radio-indicator"></span>
	Custom radio
</label>
```

## Usage

You could use a tool like [sheetify](https://github.com/stackcss/sheetify) to consume.

```js
var css = require('sheetify')

css('css-radio')
```

## Install

### npm
`npm install css-radio`

## Related
- [css-checkbox](https://github.com/frekyll/css-checkbox)
- [minimal-reset](https://github.com/frekyll/minimal-reset)
- [sheetify](https://github.com/stackcss/sheetify)
- [wtf-forms](https://github.com/mdo/wtf-forms)
