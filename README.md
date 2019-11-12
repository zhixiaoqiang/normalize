# @jzone/normalize

[@jzone/normalize] is a CSS library that provides consistent,
cross-browser default styling of HTML elements.

## Install

```sh
npm install @jzone/normalize --save
```

#### Webpack Usage

Import [@jzone/normalize] in CSS:

```css
@import '~@jzone/normalize';
```

Alternatively, import [@jzone/normalize] in JS:

```js
import '@jzone/normalize';
```

In `webpack.config.js`, use the appropriate loaders:

```js
module.exports = {
  module: {
    rules: [
      {
        test: /\.css$/,
        use: [ 'style-loader', 'css-loader' ]
      }
    ]
  }
}
```

**Download**

See https://jzone.github.io/normalize

<br/>
<br/>