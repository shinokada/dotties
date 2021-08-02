# Dotties

## Overview

Dotties is a simple dotfile management script.
It saves specified dotfiles in the home directory to a Gist and clone them from the Gist.

## Requirement

- GitHub CLI gh

Homebrew/LinuxBrew

```sh
brew install gh
```

### Warning to Ubuntu/Debian users about snap

For Ubuntu/Debian, use `apt`. `snap` won't work with hidden files.
[Download a Debian package (.ddb)](https://github.com/cli/cli/releases) and double click the downloaded file or run:

```sh
sudo apt install ./gh_1.13.1_linux_amd64.deb
```

- Python to open a browser

## Installation

Using [Awesome package manager](https://github.com/shinokada/awesome):

```sh
awesome install shinokada/dotties
```

## Usage

Create a new `.dotties` file:

```sh
dotties
```

This will pick up all dotfiles from your Home dir and write them in the `.dotties` file.

Edit the `.dotties` file to edit:

```sh
dotties -e
# or
dotties --edit
```

Your terminal editor will open the `dotties` file.

Read the `dotties` file:

```sh
dotties -r
# or
dotties --read
```

This will print your `.dotties` content on your terminal.

### Gist related options

Save files in the `.dotties` to a Gist:

```sh
dotties -G
# or
dotties --Gist
```

This will upload all your dotfiles in the `.dotties` to a Gist.
The Gist URL will be stored in the `~/.dotties/gisturl` file.

Edit the Dotties Gist

```sh
dotties -E
# or
dotties --Edit
```

The GitHub CLI will open your Gist to edit/submit/cancel.

View the Dotties Gist

```sh
dotties -V
# or
dotties --View
```

The GitHub CLI will view the Gist.

Clone the Dotties Gist

```sh
dotties -C target-dir
# or
dotties --clone
```

This will clone the dotfile Gist. If the target dir isn't given it will clone to the current directory.

Delete the Dotties Gist

```sh
dotties -D
# or
dotties --Delete
```

### Other options

List all dotfiles from your home dir:

```sh
dotties -l
# or
dotties --local
```

Print help.

```sh
dotties -h
# or
dotties --help
```

Print the version.

```sh
dotties -v
# or
dotties --version
```

## Author

Shinichi Okada

## License

Please see license.txt.
