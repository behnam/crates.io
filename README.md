# crates.io

[![Build Status](https://travis-ci.org/rust-lang/crates.io.svg?branch=master)](https://travis-ci.org/rust-lang/crates.io)

Source code for the default [Cargo](http://doc.crates.io) registry. Viewable
online at [crates.io](https://crates.io).

## Status of crates.io

Any known issues currently affecting the registry running at https://crates.io
will be posted to [@RustStatus](https://twitter.com/ruststatus).

If you are experiencing an issue not addressed there, please contact us in one
of the following ways:

- [File a new issue](https://github.com/rust-lang/crates.io/issues/new)
- Email [help@crates.io](mailto:help@crates.io)
- Chat on irc.mozilla.org in the [#rust-infra](https://kiwiirc.com/client/irc.mozilla.org:+6667/#rust-infra) channel

A volunteer will get back to you as soon as possible.

## Contributing

Welcome! We love contributions! Crates.io is an [Ember](https://emberjs.com/)
frontend with a Rust backend, and there are many tasks appropriate for a
variety of skill levels.

Please see [docs/CONTRIBUTING.md](https://github.com/rust-lang/crates.io/blob/master/docs/CONTRIBUTING.md) for ideas about what to work on and how to set up a development
environment.

<a href="https://www.browserstack.com">
    <img src="browserstack-logo.png" alt="BrowserStack" />
</a>

We also use [BrowserStack](https://www.browserstack.com) to help us verify that the frontend works in all of our supported browsers. Thanks, BrowserStack!

### Categories

Adding or editing the categories and corresponding descriptions displayed on
[crates.io/categories](https://crates.io/categories) does not require a full
development environment set up.

The list of categories available on crates.io is stored in
[`src/categories.toml`](https://github.com/rust-lang/crates.io/blob/master/src/categories.toml).
To propose adding, removing, or changing a category, send a pull request making
the appropriate change to that file as noted in the comment at the top of the
file. Please add a description that will help others to know what crates are in
that category.

For new categories, it's helpful to note in your PR description examples of
crates that would fit in that category, and describe what distinguishes the new
category from existing categories.

After your PR is accepted, the next time that crates.io is deployed the
categories will be synced from this file.

## Running a mirror

Please see [docs/MIRROR.md](https://github.com/rust-lang/crates.io/blob/master/docs/MIRROR.md) for instructions on setting up a mirror of crates.io.
