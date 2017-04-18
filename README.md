# nabg

> Seb Pearce's wonderful [New Age Bullshit Generator](http://sebpearce.com/bullshit), rolled into a Node module with some minor tweaks.

## Install

```bash
npm i -S nabg
```

## Usage

Using the module is extraordinarily simple. Simply import the module and call the ionize method.

```JavaScript
var nabg = require('nabg');

console.log(nabg.ionize(2));
// 'Where there is materialism, being cannot thrive. We can no longer afford to live with desire.'
```

- `nabg.ionize(numSentences)`: Randomly generates the requested number of sentences.


- `nabg.bs`: This object contains a variety of methods used for the actual sentence generation. This makes it easier to 
roll your own sentence generation algorithm, if you were so inclined.

## License

[MIT](http://vjpr.mit-license.org)

[npm-url]: https://npmjs.org/package/nabg
