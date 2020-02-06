# strftime.js

Ruby-like strftime method implementation in Javascript without the percentage notation.

The formatting is based on [strftime.org](http://strftime.org)

## Example

```js
console.log(new Date().strftime('H:M p - A')) // 21:32 AM - Thursday
```

```js
console.log(new Date('01/01/2018').strftime('m/b/Y')) // 1/Jan/2018
```

```js
console.log(new Date('01/18/2018').strtime('do B Y')) // 18th January 2018
```
