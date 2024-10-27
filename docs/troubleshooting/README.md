# Troubleshooting

This section provides solutions to common problems that you may encounter when using DocInsight.

## Delphi Extension

### Installation

### Restart DocInsight Server

`DocInsight > Tools > Restart DocInsight Server`

### Logs

`%LOCALAPPDATA%\DevJet\DocInsight\6.0\Logs`

- docinsight-client.log
- docinsight-server.log

## DocInsight CLI

DocInsight CLI logs all messages to the console. You can redirect the output to a file by using the `>` operator. For example:

```shell
docinsight build -v 2>&1 > build.log
```

Use `-vv`/`-vvv` to increase the verbosity of the log messages.

> [!WARNING]
>
> Logs may contain sensitive information including your source code. Make sure to review the logs before sharing them with others.

### `dry-run` mode

The `dry-run` mode allows you to simulate the build process without actually creating output files. This can be useful for testing the build process. For example:

```shell
docinsight build -vv --dry-run -f html
```
