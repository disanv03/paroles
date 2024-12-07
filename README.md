# Paroles

Minimal CLI for fetching lyrics from `genius.com`
Enjoy getting lyrics very fast and sing along your favorite song.

## Installation

Just clone the repo and launch this ruby script. No API key required !
```bash
gem install nokogiri
```

```ruby
# Necessary libraries:
# Most of them are ruby built-in libs
require 'json'
require 'net/http'
require 'nokogiri'
require 'uri'
```

## Usage

```bash
(ruby) paroles <query>

" for example:
paroles get lucky
```

## Credits

That the ruby version of [GeniusCTL](https://github.com/matisiekpl/geniusctl) based on `genius.com`
