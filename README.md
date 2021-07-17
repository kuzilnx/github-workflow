Python + Github Actions Exercise

Please fork the following github repository:
https://github.com/otomato-gh/pytest-tutorial

The repo includes a CI workflow in the following file:

https://github.com/otomato-gh/pytest-tutorial/blob/main/.github/workflows/python-package.yml

Currently the flow fails on initialization.

1. Fix the flow so it can start running

2. Once you fix it - you'll see it fails on linting
 with flake8 - please fix the linting
issues

3. The Test with pytest step now doesn't actually run the tests. Please
add test execution with verbose output

4. Add a step to publish the package with Twine
 to the following repo:

https://otomato.jfrog.io/artifactory/api/pypi/PyPi