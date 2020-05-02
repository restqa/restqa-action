# RestQa Action

> A GitHub action to run your RestQa project's test automation suite

<div align="center">
	<br>
	<img width="150" src="https://avatars1.githubusercontent.com/u/60838103?s=150&v=4" alt="RestQa">
	<br>
</div>


## What is RestQa ? 

Restqa is an open automation framework based on Gherkin.
A few step and your Test automation framework is setup. No dependency the framework is ready to be plug to all your project components

## Usage

This action runs in the [RestQa](https://hub.docker.com/repository/docker/restqa/restqa) container.

If all your feature files are in a folder called `tests`, run it like this:

```yaml
name: E2E Test

on: [push]

jobs:
  RestQa:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v1
    - uses: restqa/restqa-action@0.0.1
      with:
        path: 'test/'
```

### References

* [RestQa](http://www.restqa.io)
* [RestQa Organization](https://github.com/restqa)

### Keywords

* test automation
* Gherkin
* Cucumber
* End to End
* E2E
* Quality assurance
* QA
* Continuous integration
  
