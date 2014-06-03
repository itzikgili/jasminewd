1.0.0
=====

Support for Jasmine 1.3.1. Tested against minijasminenode @ 0.4.0.

Features

 - Automatically makes tests asynchronously wait until the WebDriverJS control flow is empty.

 - If a `done` function is passed to the test, waits for both the control flow and until done is called.

 - Enhances `expect` so that it automatically unwraps promises before performing the assertion.