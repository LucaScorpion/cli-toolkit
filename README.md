# CLI Toolkit

A collection of CLI tools, written in Bash.

## Installation

Clone this repository, e.g. to `~/bin/cli-toolkit`:

```shell
git clone git@github.com:LucaScorpion/cli-toolkit.git "$HOME/bin/cli-toolkit"
```

Add the cloned directory to your `$PATH` by adding this to your `.bashrc`, `.zshrc` or similar:

```shell
export PATH="$PATH:$HOME/bin/cli-toolkit"
```

## Updating

To update the toolkit, simply pull the repo:

```shell
git -C "$HOME/bin/cli-toolkit" pull
```

## Tools

A brief overview of all available scripts.
For more information on how to use each script, call it with the `--help` option.

| Script          | Description                                      |
|-----------------|--------------------------------------------------|
| `browser`       | Pipe HTML to your browser.                       |
| `composer-link` | Link a Composer dependency to a local directory. |
| `jwt-decode`    | Decode and display a JSON Web Token.             |
| `repo`          | Open the remote repository in your browser.      |
| `vpn`           | Connect to a VPN profile.                        |
