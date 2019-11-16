# hsl-to-hex
Convert HSL colors to RGB colors in hex format. My first test npm

## Install

```shell
npm install --save @viveklakhanpal/hsl-to-hex
```

## API

```javascript
require('hsl-to-hex') => Function
hsl(hue, saturation, luminosity)` => String
```

## Example

```javascript
var hsl = require('hsl-to-hex')
var hue = 133
var saturation = 40
var luminosity = 60
var hex = hsl(hue, saturation, luminosity)
console.log(hex) // #70c28
```

## License

ISC