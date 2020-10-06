# Foobar

A small module for converting vietnamese string to tonemarkless vietnamese.
For searching purpose in mongodb ,you should made a new Fields and save tonemarkless string in there.

## Installation

```bash
npm install vietnamese-tonemarkless

```

## Usage

```js
const removeMark = require("vietnamese-tonemarkless");
let str = removeMark("Hoàng xa,Trường xa là của Việt Nam");
console.log(str);
//hoang xa,truong xa la cua viet nam
//certainly

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
