# progress-barzz

A simple textual progress bar with a time estimation.

[![NPM Version][npm-image]][npm-url]
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/40b9022c42024111b021e34014191ba9)](https://www.codacy.com/app/tiagobertolo/progress-barzz?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bertolo1988/progress-barzz&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.org/bertolo1988/progress-barzz.svg?branch=master)](https://travis-ci.org/bertolo1988/progress-barzz)
[![dependencies Status](https://david-dm.org/bertolo1988/progress-barzz/status.svg)](https://david-dm.org/bertolo1988/progress-barzz)
[![devDependencies Status](https://david-dm.org/bertolo1988/progress-barzz/dev-status.svg)](https://david-dm.org/bertolo1988/progress-barzz?type=dev)
[![MIT License][license-image]][license-url]

```js
let Progress = require('./dist/progress-barzz');
Progress.init(10);
console.log(Progress.tick());
```


## Installing

```bash
$ npm install --save progress-barzz
````

## Usage

Only 2 methods are exported, `init` and `tick`.

Set the total amount of ticks with `init` and to increase the progress just call `tick`.

The time estimation is calculated using the time between ticks.

For further instructions check `demo.js`.


## Demo output example

	1/20 [#------------------------] 5% 0s/tick ETA:19:40:54
	2/20 [##-----------------------] 10% 0s/tick ETA:19:40:55
	3/20 [###----------------------] 15% 0s/tick ETA:19:40:56
	4/20 [#####--------------------] 20% 0s/tick ETA:19:40:56	
	5/20 [######-------------------] 25% 0s/tick ETA:19:40:57
	6/20 [#######------------------] 30% 0s/tick ETA:19:40:57
	7/20 [########-----------------] 35% 0s/tick ETA:19:40:57
	8/20 [##########---------------] 40% 0s/tick ETA:19:40:57
	9/20 [###########--------------] 45% 0s/tick ETA:19:40:57
	10/20 [############-------------] 50% 0s/tick ETA:19:40:57
	11/20 [#############------------] 55% 0s/tick ETA:19:40:57
	12/20 [###############----------] 60% 0s/tick ETA:19:40:57
	13/20 [################---------] 65% 0s/tick ETA:19:40:57
	14/20 [#################--------] 70% 0s/tick ETA:19:40:57
	15/20 [##################-------] 75% 0s/tick ETA:19:40:57
	16/20 [####################-----] 80% 0s/tick ETA:19:40:57
	17/20 [#####################----] 85% 0s/tick ETA:19:40:57
	18/20 [######################---] 90% 0s/tick ETA:19:40:57
	19/20 [#######################--] 95% 0s/tick ETA:19:40:57
	20/20 [#########################] 100% 0s/tick ETA:19:40:57


## Tests

```bash
$ npm test
```

## Contributing

Contributions, requests or pull requests are welcome & appreciated!

Send [me](https://github.com/bertolo1988/) an email if you have questions regarding possible contributions.

## License

  [MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/progress-barzz.svg
[npm-url]: https://www.npmjs.com/package/progress-barzz
[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE