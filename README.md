# make-formula

Create simple homebrew formulas from github repositories.

## Install

With [basher](https://github.com/basherpm/basher):

`$ basher install juanibiapina/make-formula`

## Usage

```
$ make-formula <user> <repo>
```

This creates a simple formula for the github repo at `<user>/<repo>`. It uses
the latest release and assumes one binary file also called `<repo>`.
