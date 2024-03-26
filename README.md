# sample-ci

The simplest CI example for Node.js

## Installation

1. Install the Node package manager:

    ```bash
    brew install npm
    ```

2. Install Jest (a popular JavaScript Testing Framework):

    ```bash
    npm install --save-dev jest
    ```

3. Check the install by running the tests:

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
