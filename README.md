# MbtaWrapper

[![Build Status](https://travis-ci.org/sicentendu/mbta_wrapper.png)](https://travis-ci.org/sicentendu/mbta_wrapper)

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'mbta_wrapper'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mbta_wrapper

## Usage

This gem provides super easy access to the MBTA's API.

    MbtaWrapper::Subway
    MbtaWrapper::CommuterRail
    MbtaWrapper::Bus
    
To view the current number of red line trains running:

    MbtaWrapper::Subway.new('red').active_trains

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
