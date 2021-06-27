# Dotties

## Overview

Dotties is a simple dotfile management script.
It saves specified dotfiles in the home directory to a Gist and recover from a Gist.

## Requirement

GitHub CLI gh
Bash version >= 4

## Installation

Using [Awesome package manager](https://github.com/shinokada/awesome):

```sh
awesome -i shinokada/dotties
```

## Usage

Create a new `.dotties` file:

```sh
dotties
```

Edit the `.dotties` file to edit:

```sh
dotties -e
# or
dotties --edit
```

Read the `dotties` file:

```sh
dotties -r
# or
dotties --read
```

Save files in the `.dotties` to a Gist:

```sh
dotties -g
# or
dotties --gist
```

Update a Gist by URL or number

```sh
dotties -u [Gist number | URL]
# or
dotties --update [Gist number | URL]
```

List all dotfiles from your home dir:

```sh
dotties -l
# or
dotties --local
```

Recover all dotties from a Gist URL.

```sh
dotties -r [Gist number | URL]
# or
dotties --recover [Gist number | URL]
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
