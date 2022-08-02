# Librarian

[![License](https://img.shields.io/github/license/voxpupuli/librarian.svg)](https://github.com/voxpupuli/librarian/blob/master/LICENSE.txt)
[![Test](https://github.com/voxpupuli/librarian/actions/workflows/test.yml/badge.svg)](https://github.com/voxpupuli/librarian/actions/workflows/test.yml)
[![Release](https://github.com/voxpupuli/librarian/actions/workflows/release.yml/badge.svg)](https://github.com/voxpupuli/librarian/actions/workflows/release.yml)
[![RubyGem Version](https://img.shields.io/gem/v/librarian.svg)](https://rubygems.org/gems/librarian)
[![RubyGem Downloads](https://img.shields.io/gem/dt/librarian.svg)](https://rubygems.org/gems/librarian)

This is a forked version published as `librarianp` with improvements in order to support `librarian-puppet`.

Librarian is a framework for writing bundlers, which are tools that resolve,
fetch, install, and isolate a project's dependencies, in Ruby.

A bundler written with Librarian will expect you to provide a specfile listing
your project's declared dependencies, including any version constraints and
including the upstream sources for finding them. Librarian can resolve the spec,
write a lockfile listing the full resolution, fetch the resolved dependencies,
install them, and isolate them in your project.

A bundler written with Librarian will be similar in kind to [Bundler](http://gembundler.com),
the bundler for Ruby gems that many modern Rails applications use.

How to Contribute
-----------------

### Running the tests

Ensure the gem dependencies are installed:

    $ bundle

Run the tests with the default rake task:

    $ [bundle exec] rake

or directly with the rspec command:

    $ [bundle exec] rspec spec

### Installing locally

Ensure the gem dependencies are installed:

    $ bundle

Install from the repository:

    $ [bundle exec] rake install

### Reporting Issues

Please include a reproducible test case.

License
-------

Written by Jay Feldblum and Carlos Sanchez.

Copyright (c) 2011-2013 ApplicationsOnline, LLC. and Carlos Sanchez

Released under the terms of the MIT License. For further information, please see
the file `LICENSE.txt`.
