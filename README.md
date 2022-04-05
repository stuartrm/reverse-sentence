# reverse-sentence

Reverses the words of a sentence.

## Install

```sh
npm install @stuartrm/reverse-sentence
```

## API

```js
require("reverse-sentence") => Function
reverse(sentence) => String
```

## Example

```js
const reverseSentence = require("reverse-sentence");
const sentence = "Hello John";
const reversed = reverseSentence(sentence);
console.log(reversed); // John! Hello
```

## License

MIT
