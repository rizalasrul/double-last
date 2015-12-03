# double-last [![Support this project][donate-now]][paypal-donations]

Doubles the last letter.

## Installation

```sh
$ npm i --save double-last
```

## Example

```js
// Dependencies
var DoubleLast = require("double-last");

console.log(DoubleLast("coffe"));
// => "coffee"

console.log(DoubleLast("coffe", ["t"]));
// => "coffe"

console.log(DoubleLast("coffe", ["e"]));
// => "coffee"
```

## Documentation

### `DoubleLast(input, letters)`
Doubles the last letter.

#### Params
- **String** `input`: The input string.
- **Array** `letters`: An array of letters: if the last letter of the input is not found in this list, it will *not* be doubled.

#### Return
- **String** The modified string.

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

 - [`name-it`](https://github.com/IonicaBizau/name-it#readme)

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md