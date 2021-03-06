# EnforceSameOrigin

Automatically sets the `X-Frame-Options` header on all requests to be `SAMEORIGIN`.  Various security scans will fail you for not having this header set. Now you can just drop this into your apps and be compliant.

## Installation

Add this line to your application's Gemfile:

    gem 'enforce_same_origin'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install enforce_same_origin

## Usage

In your `config.ru` add the following:

    use Rack::EnforceSameOrigin

## Contributing

1. Fork it ( [http://github.com/beenverifiedinc/enforce_same_origin/fork](http://github.com/beenverifiedinc/enforce_same_origin/fork) )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
