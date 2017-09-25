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

You need to install the following modules,
using cpanm. If you don't have cpanm installed, first install that using apt/yum/homebrew.

```bash
sudo cpanm Perl::Critic::Freenode Perl::Critic Perl::Tidy
```

