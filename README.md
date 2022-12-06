Rust Template
=============

A simple rust template, with all CI/CD, and chores preconfigured.

## Goal

The goal of this project is to lower the required effort to set up a repository with all required configuration.

Normally projects are quite intense at the start and you're really focussed on solving the problem at hand.
Because of this, some things slip through the cracks, like licenses, CI/CD, a simple README.
You probably end up copying those files from an other project you have, stripping most of the features and changing a couples of things.

Hopefully this projects enables me, or you, to change this and start a project a couple of good ideas to start.

## Usage

To initialise this project you can use [cargo-generate](https://github.com/cargo-generate/cargo-generate):

```
cargo generate DanielVoogsgerd/rust-template template
```

## Included:

There are a couple of things included, suggested, and assumed by this template:

### Semantic versioning / release

This project heavily relies on the concept of [Angular.js' commit message format].
It is used in CD to create automatic releases with meaningful changelog.

### Issue / PR Templates

A minimal and common bug-report, feature request and PR template is included, so that conversations can stay meaningful.
