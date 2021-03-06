# Rateless Bot

This is an IRC Bot that I made for my IRC channel. I figured other people might want to use it.

## Installation

If you haven't already, install RubyGems. You can do this with your package manager or with [RVM](https://rvm.io)

Once you have RubyGems, simply install it like so:

    $ gem install rateless_bot

## Usage
Launch Options:

    $ rateless_bot -h
    Usage: rateless_bot [options]
            --nick NICK                    Bot's nick (required)
            --server SERVER                IRC server (required)
            --channel CHANNEL              IRC channel (required)
            --lastfm-api-key KEY           LastFM API key
            --lastfm-api-secret SECRET     LastFM secret API key
	    --open-weather-map-api-key KEY OpenWeatherMap API key

        -h, --help                       Prints this help

Interacting with the bot:

    <vheuken> !help
    -Rateless-Bot- List of commands:
    -Rateless-Bot- !flipcoin - flips a coin
    -Rateless-Bot- !roll XdY - rolls dice (replace X with number of dice and Y with number of sides)
    -Rateless-Bot- !lastfm USERNAME - gets the most recently listened-to track for a given user
    -Rateless-Bot- !8ball - Magic Eight Ball
    -Rateless-Bot- !weather CITY/ZIP - gets the current temperature for a given city/zip 

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/[my-github-username]/rateless_bot/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
