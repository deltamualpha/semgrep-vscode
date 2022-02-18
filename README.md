⚠️ NOTE: This project is experimental and not actively maintained by r2c ⚠️

# semgrep-vscode

A Visual Studio Code extension for [Semgrep](https://github.com/returntocorp/semgrep).

- See Semgrep scan results inline each time you save a file
- Choose which Semgrep rules you run by setting semgrep.rules in Visual Studio Code

## Prerequisites

You will need to install `semgrep` yourself.
You can do so with

```sh
pip install semgrep
```

For other installation instructions, see the [Semgrep README](https://github.com/returntocorp/semgrep#getting-started).

## Configuration

You can set the following options by going to Preferences > Settings:

### `semgrep.languages`

Languages to run Semgrep scans on.
By default, this is set to all supported languages.

### `semgrep.rules`

Rules to scan with. This will be passed as `--config` to the `semgrep` CLI.
By default, it's set to <https://semgrep.dev/p/r2c>.

## Support

Please join the [Semgrep community Slack workspace](https://r2c.dev/slack)
for support if you run into problems.
