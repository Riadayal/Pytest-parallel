# How to run parallel automation tests in Pytest on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Pytest-parallel)

If you want to run parallel automation tests in Pytest on Lambdatest, you can use the following steps. You can refer to sample test repo [here](https://github.com/LambdaTest/pytest-selenium-sample).

# Steps:

Ensure that pytest package is installed by running:
```bash
pip install pytest-selenium
```

To run parallel tests using PyTest, we would have to execute the below command in the terminal:

```bash
pytest -s -n=2 tests/lt_sample_todo.py
```

In the above command, we have used -s to disable the output capture & -n is used to specify the number of parallel test execution. Your test results would be displayed on the test console (or command-line interface if you are using terminal/cmd) and on [LambdaTest automation dashboard](https://automation.lambdatest.com/build).

# Links:

[LambdaTest Community](http://community.lambdatest.com/)

