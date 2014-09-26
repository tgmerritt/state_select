Refactored by [danijel] to use country codes instead of full names, easier to use with country_select,
added rescue from NameError if no states array for requested country exists

# StateSelect

`state_select` plugin allows you to easily create dropdown list of states for a country provided as an option.

Default country is US.

## Usage

    state_select(object, method, country = "US", options = {}, html_options = {})

Currently it supports:

* INDIA,
* US (Long and Short Names),
* UK,
* CANADA,
* AUSTRALIA,
* SPAIN,
* FRANCE,
* UGANDA,
* GERMANY,
* NETHERLANDS,
* MEXICO,
* JAPAN,
* POLAND.

## Compatibility

`state_select` works with Rails 2.3, 3.0, 3.1 and 3.2.

## Contributors

* Thanks [keith](http://rubygreenblue.com/) for Australian states
* Thanks [Vicent](http://www.vicentgozalbes.com/) for Spanish states
* Thanks Chuck Phillips for Ugandan states
* Thanks Jonathan Tron for French states
* Thanks [Gavin Morrice](http://handyrailstips.com/) for UK States
* Thanks [Filip Tepper](http://tepper.pl/) for Polish States
