# Gift Giver - simple TDD practice with react

### To run test
npm run test

### To run test with coverage report
npm run test -- --coverage

To specify files convered in the test report.
Example below.

### package.json
```
  "jest": {
    "collectCoverageFrom": [
      "src/**/*.js",
      "!src/index.js",
      "!src/tempPolyfills.js"
    ]
  }
```
As you can see, add ! in front of the file name.  This will exclude the file from the test report.