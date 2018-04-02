# webpack-staticmap-plugin
[![npm](https://img.shields.io/npm/v/webpack-staticmap-plugin.svg?style=plastic)](https://www.npmjs.com/package/webpack-staticmap-plugin)

generate assets map of webpack(v4) compilation

## Usage
`webpack.config.js`:
```javascript
{
  module: {
    rules: [...]
  },
  plugins: [
    new StaticMapPulgin({
      // options
    })
  ]
}
```

## Options
- `outputfile`: specific name of the generated file, `static.json` by default;
- `dev`: enable/disable development mode.

> assets map info would be assigned to global varable under development mode.