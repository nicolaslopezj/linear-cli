linear-cli
==========

An unoffical CLI for [Linear](https://linear.app/)

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/linear-cli.svg)](https://npmjs.org/package/linear-cli)
[![Downloads/week](https://img.shields.io/npm/dw/linear-cli.svg)](https://npmjs.org/package/linear-cli)
[![License](https://img.shields.io/npm/l/linear-cli.svg)](https://github.com/egodon/linear-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @evangodon/lr
$ lr COMMAND
running command...
$ lr (-v|--version|version)
@evangodon/lr/0.2.0 linux-x64 node-v15.6.0
$ lr --help [COMMAND]
USAGE
  $ lr COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`lr config:delete`](#lr-configdelete)
* [`lr config:show`](#lr-configshow)
* [`lr help [COMMAND]`](#lr-help-command)
* [`lr init`](#lr-init)
* [`lr issue [FILE]`](#lr-issue-file)
* [`lr issue:create`](#lr-issuecreate)
* [`lr issue:list`](#lr-issuelist)
* [`lr issue:show ISSUEID`](#lr-issueshow-issueid)
* [`lr issue:update ISSUEID`](#lr-issueupdate-issueid)
* [`lr workspace:add`](#lr-workspaceadd)
* [`lr workspace:switch`](#lr-workspaceswitch)

## `lr config:delete`

```
USAGE
  $ lr config:delete
```

_See code: [src/commands/config/delete.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/config/delete.ts)_

## `lr config:show`

```
USAGE
  $ lr config:show
```

_See code: [src/commands/config/show.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/config/show.ts)_

## `lr help [COMMAND]`

display help for lr

```
USAGE
  $ lr help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_

## `lr init`

```
USAGE
  $ lr init
```

_See code: [src/commands/init.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/init.ts)_

## `lr issue [FILE]`

describe the command here

```
USAGE
  $ lr issue [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/issue/index.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/issue/index.ts)_

## `lr issue:create`

Create a new issue

```
USAGE
  $ lr issue:create
```

_See code: [src/commands/issue/create.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/issue/create.ts)_

## `lr issue:list`

List issues

```
USAGE
  $ lr issue:list

OPTIONS
  -m, --mine
  -x, --extended          show extra columns
  --columns=columns       only show provided columns (comma-separated)
  --csv                   output is csv format [alias: --output=csv]
  --filter=filter         filter property by partial string matching, ex: name=foo
  --no-header             hide table header from output
  --no-truncate           do not truncate output to fit screen
  --output=csv|json|yaml  output in a more machine friendly format
  --sort=sort             property to sort by (prepend '-' for descending)
```

_See code: [src/commands/issue/list.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/issue/list.ts)_

## `lr issue:show ISSUEID`

Show description of issue

```
USAGE
  $ lr issue:show ISSUEID
```

_See code: [src/commands/issue/show.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/issue/show.ts)_

## `lr issue:update ISSUEID`

Update an issue

```
USAGE
  $ lr issue:update ISSUEID

OPTIONS
  -s, --status  Update issue status
```

_See code: [src/commands/issue/update.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/issue/update.ts)_

## `lr workspace:add`

Add a new workplace

```
USAGE
  $ lr workspace:add
```

_See code: [src/commands/workspace/add.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/workspace/add.ts)_

## `lr workspace:switch`

Switch to another workspace

```
USAGE
  $ lr workspace:switch
```

_See code: [src/commands/workspace/switch.ts](https://github.com/egodon/linear-cli/blob/v0.2.0/src/commands/workspace/switch.ts)_
<!-- commandsstop -->
