# Instajs-docs

A parser and wrapper for the [insta.js](https://github.com/Androz2091/insta.js) docs based on `discord.js-docs`.

# Example

```js
const Docs = require('instajs-docs')

Docs.fetch('master')
  .then((doc) => {
    console.log(doc.resolveEmbed('client'))
  })


```