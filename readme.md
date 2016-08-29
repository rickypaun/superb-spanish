# superb-spanish [![Build Status](https://travis-ci.org/rickypaun/superb-spanish.svg?branch=master)](https://travis-ci.org/rickypaun/superb-spanish)

> Get superb like words in Spanish

The word list itself is just a [JSON file](words.json) and can be used wherever.


## Install

```
$ npm install --save superb-spanish
```


## Usage

```js
const superbSpanish = require('superb-spanish');

superbSpanish();
//=> 'maravilloso'

superbSpanish();
//=> 'alucinante'

superbSpanish.words
// ['alucinante',	'asombroso', ...]
```


## API

### superbSpanish()

#### input

Type: `string`

Random [superb like word](words.json).

#### options

##### superbSpanish.words

Type: `array`

All the words


## CLI

```
$ npm install --global superb-spanish
```

```
$ superb-spanish --help

	Examples
	  $ superb-spanish
	  legendario

	  $ superb-spanish --all
		  alucinante
		  asombroso
		  ...

		Options
	  --all  Get all the words instead of a random word
```


## License

MIT © [Ricky Paun](https://github.com/rickypaun)
