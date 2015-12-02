# Grnlip

[![Gem Version](https://badge.fury.io/rb/grnlip.svg)](http://badge.fury.io/rb/grnlip)

A command line interface for [Groonga](http://groonga.org/).

## TODO

* Support multiline input.

## Installation

    $ gem install grnlip

## Usage

    $ grnlip GROONGA_EXE_PATH DB_PATH [DB_ENCODING]

For example:

    $ grnlip groonga ~/.milkode/db/milkode.db

If you use UTF-8 database on Windows, you should specify the following option to use multibyte characters:

    > grnlip bin\groonga \Users\myokoym\.milkode\db\milkode.db utf-8

Then, REPL by Readline for Groonga is started:

    > status

And, you can use pretty-print:

    > pp status

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake false` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/myokoym/grnlip.

