# docker build action with maven, jdk11, make and heroku

This action provides a docker container with above programs installed

## Inputs

### `command`

**Required** command to execute in order to build, deploy your project. Default `make`.


## Example usage

uses: actions/build-mvn-jdk11-heroku@v1
with:
    command: make package d-build deploy