# Difficult Customer plugin
Difficult Customer is a plugin that helps you to motivate your customers to settle payments.

## Usage
To use the plugin just place this helper in your layout file: `difficult_customer`.

## Installation
Add this line to your application's Gemfile:

```ruby
gem 'difficult-customer'
```

And then execute:
```bash
$ bundle
```

Or install it yourself as:
```bash
$ gem install difficult-customer
```

By default, this gem will use config file from example/difficult_customer.yml which contains sample configuration.
To use your own, use:
```bash
$ rails generate difficult_customer:install
```
and adjust difficult_customer.yml file from your application's config/ directory.

## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
