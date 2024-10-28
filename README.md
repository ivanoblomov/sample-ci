# sample-ci

The simplest Continuous-Integration example for Node.js

## Installation

1. Install the Node package manager:

    ```bash
    brew install npm
    ```

2. Configure `package.json` for the desired testing framework. To use Jest, for example, add the following:

    ```bash
    "devDependencies": {
      "jest": "^29.7"
    }
    ```

3. Install the test framework configured in 2:

    ```bash
    npm install
    ```

4. Perform a clean install:

    ```bash
    npm ci
    ```

5. Check the install by running the tests:

    ```bash
    npm test
    ```

    If all is well, you should see output similar to this:

    ```bash
    $ npm test

    > test
    > jest

     PASS  ./sum.test.js
      ✓ adds 1 + 2 to equal 3 (1 ms)

    Test Suites: 1 passed, 1 total
    Tests:       1 passed, 1 total
    Snapshots:   0 total
    Time:        0.163 s
    Ran all test suites.
    ```

## Credits

Adapted from Jest's [Getting Started](https://jestjs.io/docs/getting-started) tutorial.
