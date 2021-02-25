@chaalaa/hub
============

A simple PaaS implementation for managing and deploying different versions of projects for UAT.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@chaalaa/hub.svg)](https://npmjs.org/package/@chaalaa/hub)
[![Downloads/week](https://img.shields.io/npm/dw/@chaalaa/hub.svg)](https://npmjs.org/package/@chaalaa/hub)
[![License](https://img.shields.io/npm/l/@chaalaa/hub.svg)](https://github.com/chaalaa/hub/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @chaalaa/hub
$ chaalaa-hub COMMAND
running command...
$ chaalaa-hub (-v|--version|version)
@chaalaa/hub/0.0.0 darwin-x64 node-v12.20.0
$ chaalaa-hub --help [COMMAND]
USAGE
  $ chaalaa-hub COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`chaalaa-hub hello [FILE]`](#chaalaa-hub-hello-file)
* [`chaalaa-hub help [COMMAND]`](#chaalaa-hub-help-command)

## `chaalaa-hub hello [FILE]`

describe the command here

```
USAGE
  $ chaalaa-hub hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ chaalaa-hub hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/chaalaa/hub/blob/v0.0.0/src/commands/hello.ts)_

## `chaalaa-hub help [COMMAND]`

display help for chaalaa-hub

```
USAGE
  $ chaalaa-hub help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
