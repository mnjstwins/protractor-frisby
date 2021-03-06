### Get Started
Clone this repo and go into the current directory and run:

```
npm install
```
### Run frisby & protractor tests

```
npm run regression_tests
```
**Note:** You need frisby version 2 to run with protractor
### Run frisby tests
```
npm run api_tests
```
**Note:** uses v0.8.5 which is not compatible with Jasmine2 & protractor
you should see the following output in console:

![frisby_output](https://cloud.githubusercontent.com/assets/15998104/21527460/84680b6a-cd51-11e6-9814-d78613cbe03b.PNG)

`jasmine-node` is used to run the tests which could is configured in `scripts` section of package.json

**Note:** The naming convention/valid specs should be - `test-name-spec.js` or `*_spec.js`
For more details please refer the following links:
* [frisby.js/examples](https://github.com/vlucas/frisby/tree/master/examples)
* [JSON placeholder- Test REST API's](https://jsonplaceholder.typicode.com/)
* [frisbyv2/examples](https://github.com/vlucas/frisby/issues/316)
