# Glimpse::PG

Provide a glimpse into the Postgres queries made during your application's requests.

Things this glimpse view provides:

- Total number of Postgres queries called during the request
- The duration of the queries made during the request

## Installation

Add this line to your application's Gemfile:

    gem 'glimpse-pg'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install glimpse-pg

## Usage

Add the following to your `config/initializers/glimpse.rb`: 

```ruby
Glimpse.into Glimpse::Views::PG
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
