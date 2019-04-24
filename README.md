<img src="https://user-images.githubusercontent.com/8289478/56633099-d6357d00-662a-11e9-9592-0c58dab8ca55.png" width="300" height="72" />

SMARTA is a very thin wrapper around the
[MARTA APIs](http://www.itsmarta.com/app-developer-resources.aspx) supplemented
with analysis of historic patterns and static schedule data.

## Continuous Integration Status

[![Continuous Integration status](https://secure.travis-ci.org/csmith-cb/smarta-api.png)](http://travis-ci.org/csmith-cb/smarta-api)
[![codecov](https://codecov.io/gh/csmith-cb/smarta-api/branch/master/graph/badge.svg)](https://codecov.io/gh/csmith-cb/smarta-api)



## Project Goals

Goals? Oh we've got goals - check 'em out in the
[overview document](doc/overview.md).

### TODO

- [x] Find rail schedule by line
- [x] Find rail schedule by station
- [x] Find bus schedule by stop
- [x] Find bus stop by route
- [ ] Find routes by stop
- [ ] Add projected arrival/departure time based on historical trends
- [ ] Create `with-credentials` wrapper for non-env credential flexibility

## Project Maturity

SMARTA is _very_ young. Young, scrappy, and hungry. 😎

## Prerequisites

You will need a [MARTA API key](https://www.itsmarta.com/developer-reg-rtt.aspx)
to fetch the live results from MARTA's base API.

You will need [Leiningen][] 2.0.0 or above installed.

[leiningen]: https://github.com/technomancy/leiningen

## Running

To start a web server for the application, run:

    lein ring server

## Tests

To run tests for the application, run:

    lein test

## License

Copyright© 2019 Interesting Times Gang.

Distributed under the GNU Public License version 3
