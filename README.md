# Basic TestCafe API example with LambdaTest

*A set of sample tests that illustrate how to use TestCafe API with LambdaTest*

## Running the example

Clone the repository to your machine and install the dependencies:

```sh
git clone https://github.com/LambdaTest/testcafe-sample.git
npm install -g testcafe
npm install
export LT_USERNAME=<Username>
export LT_ACCESS_KEY=<Access Key>
#single
testcafe "lambdatest:Chrome@74.0:Windows 8" "test.js"
#parallel
testcafe -c 2 "lambdatest:Chrome@74.0:Windows 8" "test.js"

#parallel on different combo
testcafe -c 2 "lambdatest:Chrome@77.0:Windows 8","lambdatest:Chrome@76.0:Windows 10" "test.js"
```
## About LambdaTest

[LambdaTest](https://www.lambdatest.com/) is a cloud based selenium grid infrastructure that can help you run automated cross browser compatibility tests on 2000+ different browser and operating system environments. All test data generated during testing including Selenium command logs, screenshots generated in testing, video logs, selenium logs, network logs, console logs, and metadata logs can be extracted using [LambdaTest automation APIs](https://www.lambdatest.com/support/docs/api-doc/). This data can then be used for creating custom reports.
