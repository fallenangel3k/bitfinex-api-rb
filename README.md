# Bitfinex API client Library

[![Code Climate](https://codeclimate.com/repos/56db27e5b86182573b0045ed/badges/bd763083d70114379a41/gpa.svg)](https://codeclimate.com/repos/56db27e5b86182573b0045ed/feed)

## Installation

Add this line to your application's Gemfile:

    gem 'bitfinex'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install bitfinex

## Usage

Configure your gem as:

```
Bitfinex::Client.config do |conf|
  conf.secret = ENV["BFX_API_SECRET"]
  conf.api_key = ENV["BFX_API_KEY"]
end
```

Then you can use the client as follow:

```
client = Bitfinex::Client.new
client.balance
```

check the [Bitfinex API documentation](http://docs.bitfinex.com/) for more information.

## Contributing

1. Fork it ( https://github.com/[my-github-username]/bitfinex/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
