# vegeta-runner

Vegeta load test environment

## Install

To install environment, the vegeta, please run:

`make install`

To force and version:

`make install VG_VERSION=x.x.x`

If you already have installed you can force the download:

`make download`
OR
`make upgrade`
OR
`make clean && make install`

## Setup

To setup environment, please create config files inside input directory. See [Readme](input/README.md)

## commands

### run

To run the tests please refeer to the test plan:

`make run INPUT_PLAN=input/sample-plan.txt`
