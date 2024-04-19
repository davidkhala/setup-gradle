# Setup Gradle
Setup Gradle without pre-requisite
## Usage
```
on: push
jobs:
  gradle:
    strategy:
      matrix:
        os: [ubuntu-latest, windows-latest, macos-latest]
    runs-on: ${{ matrix.os }}
    steps:
    - uses: davidkhala/setup-gradle@main
```
