# apidown [![Build Status](https://travis-ci.org/froehlichA/apidown.svg?branch=master)](https://travis-ci.org/froehlichA/apidown) [![Coverage Status](https://coveralls.io/repos/github/froehlichA/apidown/badge.svg?branch=master)](https://coveralls.io/github/froehlichA/apidown?branch=master)
:arrow_double_down: A middleman for APIs. Download, cache, get 100% uptime.

## History
This application is beginner-friendly, and made for [Hacktoberfest 2017](https://hacktoberfest.digitalocean.com/), and should serve as a starting point for javascript open-source developers.

If you would like to contribute, follow [Contributing.md](CONTRIBUTING.md).

## Technical Notice

### Automatic JSON Parser

You can set `options.parseJson` to `true` in order to automatically parse return body as JSON object. In case your input endpoint does't capable to return JSON format, the underlying system will handle error case and normally return error.

## About
With V1.0, this application should:

- parse a regexp URL input
- download the files from the URLs specified
- provide an interface for the URLs, like an REST API

For more information about how the app should work out, check out [App.md](APP.md).
