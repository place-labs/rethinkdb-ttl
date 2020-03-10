# rethinkdb-ttl

A little tool to look for documents with configurable TTL field.
Once a document has expired, it is removed from the database.

--------------------------------------------------------------------

`rethinkdb-ttl` exposes configuration through environment variables..
- `RETHINKDB_TTL_FIELD` defaults to "TTL"

## Installation

`$ shards build && ./bin/rethinkdb-ttl`

## Usage

Best deployed as a sidecar service or process alongside RethinkDB.

## Contributing

1. Fork it (<https://github.com/place-labs/rethinkdb-ttl/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [Caspian Baska](https://github.com/caspiano) - creator and maintainer
