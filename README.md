# Digest::Whirlpool - Ruby interface to the Whirlpool message digest algorithm

## Summary

Digest::Whirlpool is a Ruby library for calculating message digests
using the Whirlpool algorithm.  The library interface conforms to the
standard Digest API.

More information about Whirlpool:

- http://en.wikipedia.org/wiki/Whirlpool_%28algorithm%29
- http://planeta.terra.com.br/informatica/paulobarreto/WhirlpoolPage.html

The C code is based on the sample implementation, as available on the
mentioned website.

## Requirements

- Ruby 2.2 or later

## Usage

In Gemfile:

    gem "digest-whirlpool"

In your ruby code:

    require "digest"

    p Digest::Whirlpool.hexdigest("")	# The module is auto-loaded

## License

See the file LICENSE.
