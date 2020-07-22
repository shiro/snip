# Snip

A recipe based file generator.


## Usage

Snip can be invoked directly and will present a list of available recipes:
```
$ snip
```

Snip can receive various arguments depending on the recipe used, for example the React scripts provided with the package
can accept a relative or absolute path for component generation:
```
$ snip src/ExampleComponent
```


## Prerequisites

The following dependencies must be installed:

- [fzf](https://github.com/junegunn/fzf)
- [jq](https://github.com/stedolan/jq)

## Installation

Simply symlink the `snip.zsh` script to a location in your path.

For example:
```
$ sudo ln -s snip.zsh /usr/local/bin/snip
```

Snip will utilize the `$EDITOR` environmental variable for interactive file editing, in order to use a specific editor
simply set the variable accordingly.

## Authors

shiro <shiro@usagi.io>

## Licesne

MIT
