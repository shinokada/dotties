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

Open the `.dotties` file to edit:

```sh
dotties -o
# or
dotties --open
```

Save files in the `.dotties` to a Gist:

```sh
dotties -g
# or
dotties --gist
```

Update a Gist by URL or number

```sh
dotties -u [number|URL]
# or
dotties --update [number|URL]
```

List all dotfiles from your home dir:

```sh
dotties -l
# or
dotties --local
```

Recover all dotties from a Gist URL.

```sh
dotties -r [number | URL]
# or
dotties --recover [number | URL]
```

## Author

Shinichi Okada

## License

Please see license.txt.
