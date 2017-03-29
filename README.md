[![Code Climate](https://codeclimate.com/github/mikespencer/fe-unit-testing-starter/badges/gpa.svg)](https://codeclimate.com/github/mikespencer/fe-unit-testing-starter)

# FE Unit Testing Starter

JavaScript unit testing skeleton

## Getting started

1. Clone this repo
2. Make sure you have the [Node.js](https://nodejs.org/en/) installed
3. Run `npm install` to install dependencies
4. Run tests in watch mode with `npm test`

## Writing Tests
Any files with a `.test.js` extension inside `src/` will be run by Karma.

## Jasmine
If you aren't familiar with Jasmine, have a look at [the docs](http://jasmine.github.io/2.4/introduction.html)

## Tip

Use the following template for writing the tests:

```js
describe('what are you testing?', () => {
	it('should do a specific behaviour', () => {
		const expected = 'expected result';
		const actual = 'actual result';
		expect(actual).toEqual(expected);
	});
});
```
