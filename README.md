# Paroles

Minimal CLI for fetching lyrics from `genius.com` on a terminal

## Installation

Just clone the repo and launch this ruby script. No API key required !
```bash
gem install nokogiri
```

```ruby
# Necessary libraries:
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
