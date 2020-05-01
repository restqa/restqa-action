# RestQa Action

> A GitHub action to run your RestQa project's test automation suite

## Usage

This action runs in the [RestQa](https://hub.docker.com/repository/docker/restqa/restqa) container.

If all your feature files are in a folder called `tests`, run it like this:

```yaml
name: CI

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v1
    - uses: restqa/restqa-action@0.0.1
      with:
        path: 'k8s/*'
```
