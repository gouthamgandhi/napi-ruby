MaluubaNapi
===========

Maluuba nAPI is a new API that allows developers to add Natural Language Understanding (NLU)
to their software.

Features
--------

This API currently supports 22 different domains and around 70 different intents or actions.
We also parse out numerous entities. We believe that this API is the beginning of something great,
something that is going to completely change how people interact with their devices. But it is
just a beginning. We are starting out with the given domains, but plan on massively expanding it as
feature requests come in, and we see how people want to use this technology.

Access
------

Please sign up at the [Maluuba Developer Site](http://developer.maluuba.com) and apply for access.
We are currently in an alpha stage right now, and giving out API keys to interested third parties.
Once you have been approved, you will receive an API key that you can use with this client.

## Installation

Add this line to your application's Gemfile:

    gem 'maluuba_napi'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install maluuba_napi

## Usage

```ruby
>> client = MaluubaNapi::Client.new 'your_apikey_here'
>> client.interpret phrase: 'who is barack obama'
>> client.normalize phrase: 'tomorrow', type: 'daterange', timezone: 'EST'

```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
