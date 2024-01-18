# Zero Allocation JSON Logger with Infobip SMS

[![godoc](http://img.shields.io/badge/godoc-reference-blue.svg?style=flat)](https://godoc.org/github.com/rs/zerolog) [![license](http://img.shields.io/badge/license-MIT-red.svg?style=flat)](https://raw.githubusercontent.com/rs/zerolog/master/LICENSE) [![Build Status](https://github.com/rs/zerolog/actions/workflows/test.yml/badge.svg)](https://github.com/rs/zerolog/actions/workflows/test.yml) [![Go Coverage](https://github.com/rs/zerolog/wiki/coverage.svg)](https://raw.githack.com/wiki/rs/zerolog/coverage.html)

The zerolog-sms package provides a fast and simple logger dedicated to JSON output with an added SMS mobile logging 
level using the [Infobip API](https://www.infobip.com/docs/api/channels) and the [Infobip API Go SDK](https://github.com/infobip-community/infobip-api-go-sdk).

This project is only for demonstration purposes. To use this version, clone this repo and add a `replace` statement to your project's `go.mod` file. For example:

```
replace github.com/rs/zerolog v1.31.0 => ../../Projects/zerolog-sms
```

Zerolog's API is designed to provide both a great developer experience and stunning [performance](#benchmarks). Its unique chaining API allows zerolog to write JSON (or CBOR) log events by avoiding allocations and reflection.

To know more details about the original zerolog, please read their [Readme](https://github.com/rs/zerolog).