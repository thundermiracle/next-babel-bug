# next-babel-bug

High-Order-Component in _document with babel.config.js throws error:

```js
TypeError: Class constructor Document cannot be invoked without 'new'
    at new withMakeDocument (C:\Users\cisso\code\nodejs\next-babel-bug\.next\server\static\development\pages\_document.js:141:247)
    at processChild (C:\Users\cisso\code\nodejs\next-babel-bug\node_modules\react-dom\cjs\react-dom-server.node.development.js:2846:14)
    at resolve (C:\Users\cisso\code\nodejs\next-babel-bug\node_modules\react-dom\cjs\react-dom-server.node.development.js:2812:5)
    at ReactDOMServerRenderer.render (C:\Users\cisso\code\nodejs\next-babel-bug\node_modules\react-dom\cjs\react-dom-server.node.development.js:3202:22)
    at ReactDOMServerRenderer.read (C:\Users\cisso\code\nodejs\next-babel-bug\node_modules\react-dom\cjs\react-dom-server.node.development.js:3161:29)
    at Object.renderToStaticMarkup (C:\Users\cisso\code\nodejs\next-babel-bug\node_modules\react-dom\cjs\react-dom-server.node.development.js:3661:27)
    at renderDocument (C:\Users\cisso\code\nodejs\next-babel-bug\node_modules\next-server\dist\server\render.js:90:18)
    at Object.renderToHTML (C:\Users\cisso\code\nodejs\next-babel-bug\node_modules\next-server\dist\server\render.js:270:16)
    at <anonymous>
```