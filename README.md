# Strings

[![Gem Version](https://badge.fury.io/rb/strings.svg)][gem]

[gem]: http://badge.fury.io/rb/strings

> The `Strings` is a set of useful functions such as wrap, truncate, indent, and many more for transforming strings.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'strings'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install strings

## Features

* No monkey-patching String class
* Functional API that can be easily wrapped by other objects
* Supports multibyte character encodings such as UTF-8, EUC-JP
* Handles languages without whitespaces between words (like Chinese and Japanese)
* Supports ANSI escape codes

## Contents

* [1. Usage](#1-usage)

## 1. Usage

```ruby
text = "Think not, is my eleventh commandment; and sleep when you can, is my twelfth."
Strings.wrap text, 30
# =>
#  "Think not, is my eleventh"
#  "commandment; and sleep when"
#  "you can, is my twelfth."

```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/piotrmurach/strings. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

1. Fork it ( https://github.com/piotrmurach/verse/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Strings project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/piotrmurach/strings/blob/master/CODE_OF_CONDUCT.md).

## Copyright

Copyright (c) 2017 Piotr Murach. See LICENSE for further details.
