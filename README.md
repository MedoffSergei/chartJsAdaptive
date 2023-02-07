# Sleep
Function `sleep` for JavaScript. 
>sleep(seconds) -> Promise
## Installation

    npm i ChartJsAdaptiv

## Usage

```js
const sleep = require('ChartJsAdaptiv');
const test = async () => {
	console.log('text1');
	await sleep(2); //sleep for 2 seconds
	console.log('text2');
};
test();
```