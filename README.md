# Hello world docker action

[![.github/workflows/main.yml](https://github.com/rajgupt/hello-world-docker-action/actions/workflows/main.yml/badge.svg)](https://github.com/rajgupt/hello-world-docker-action/actions/workflows/main.yml)  [![Docker Image CI](https://github.com/AlmaBetter-School/hello-world-docker-action/actions/workflows/docker-image.yml/badge.svg)](https://github.com/AlmaBetter-School/hello-world-docker-action/actions/workflows/docker-image.yml)

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
