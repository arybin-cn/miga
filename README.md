# Miga

Miga comes from abbr of "MIGrate Address", it's a ruby gem that utilize [udis86ext](https://github.com/arybin-cn/udis86ext) to provide some useful apis and a REPL tool to help analyse binary dump files. Particularly, Miga aims at migrating marked addresses from old dump file to the new one by automatically generating and verifying instruction-level signatures.

Still under developing, simple demo picture:
![image](https://github.com/arybin-cn/miga/blob/master/demo.png)

## Instruction Set

Currently support x86/x86-64 instruction set

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'miga'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install miga

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/arybin-cn/miga.
