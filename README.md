# README

This is a bundle I use to work on bugzilla.
It includes support for additional syntaxes required by bugzilla:

* template toolkit
* apache config
* docker config
* YAML
* extended auto-closing-tags

It also adds support for code formatting (perltidy) and linting (perlcritic).

In the future it might include better syntax highlighting for perl as VSCode's is a little lacking for new features.

## Required Setup

The commands "perlcritic" and "perltidy" need to be in the path.
Additionally, perlcritic requires Perl::Critic::Freenode.
Typically you'd install these with the cpanm command.

### OSX

Using homebrew:

```bash
brew install perl
brew install cpanminus
cpanm Perl::Critic::Freenode Perl::Critic Perl::Tidy
```

### Windows

TODO

### Linux (Ubuntu)

