# build-nginx-unit

`DISCLAMER: THIS IS NOT YET READY.`

## the goal

The goal is to have a set of scripts that would

1. build and install the NGINX UNIT in the specified directories
2. build NodeJS module and package it for self-contained installation suitable for simple `pnpm install` and without any external dependencies.

The `install` step mentioned above should create required directories and populate them with the appropriate files. These directories `should be suitable` for packaging in a countainer.

NOTE for [@mar0x](https://github.com/mar0x):

1. please run `./scripts/build-unit` to see how it goes
2. I need your help in figuring out how the `./scripts/build-unit` script should be propertly composed to produce a standalone gzip of the node module suitable for distribution.
