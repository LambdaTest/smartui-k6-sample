# smartui-k6-sample
Sample for visual regression tests run with K6

## Pre-requisites

1. Clone the repository: `git clone https://github.com/LambdaTest/smartui-k6-sample.git`
2. Install k6. Refer the installation guide here: https://k6.io/docs/get-started/installation/
3. Set the LambdaTest user and access key in environment.

**Windows**

```js
set LT_USERNAME = "YOUR_LAMBDATEST_USERNAME"
set LT_ACCESS_KEY = "YOUR_LAMBDATEST_ACCESS_KEY"
```

**macOS/Linux**

```js
export LT_USERNAME = "YOUR_LAMBDATEST_USERNAME"
export LT_ACCESS_KEY = "YOUR_LAMBDATEST_ACCESS_KEY"
```

## Running the test

Run the test with the following command:

```shell
K6_BROWSER_ENABLED=true k6 run k6-smartui.js
```

Navigate to the [LambdaTest dashboard](https://automation.lambdatest.com/build) to view the running test.
