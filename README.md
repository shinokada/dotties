# Dotties

## Overview

Dotties is a simple dotfile management script.
It saves specified dotfiles in the home directory to a Gist and clone them from the Gist.

## Requirement

GitHub CLI gh

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

### Gist related options

Save files in the `.dotties` to a Gist:

```sh
dotties -G
# or
dotties --gist
```

Update the Dotties Gist

```sh
dotties -U
# or
dotties --updategist
```

Clone the Dotties Gist

```sh
dotties -C
# or
dotties --clone
```

Delete the Dotties Gist

```sh
dotties -D
# or
dotties --delete
```

Edit the Dotties Gist

```sh
dotties -E
# or
dotties --Edit
```

Update a Gist by URL or number

```sh
dotties -u [Gist number | URL]
# or
dotties --update [Gist number | URL]
```

-E | --Edit


### Other options

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
