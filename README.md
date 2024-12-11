# Paroles

Minimal CLI for fetching lyrics from `genius.com`.


You can get lyrics very quiclky and sing along with your favorite song.

## Installation

Just clone the repo and launch this ruby script. No API key required !

```ruby
# Necessary libraries:
# Most of them are ruby built-in libs
require 'json'
require 'net/http'
require 'nokogiri'
require 'uri'
```

```bash
gem install nokogiri
```

## Usage

```bash
(ruby) paroles <query>

" for example:
paroles get lucky
```

## Credits

That the ruby version of [GeniusCTL](https://github.com/matisiekpl/geniusctl) feel free to have a look.
