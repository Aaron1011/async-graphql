# The GraphQL server library implemented by rust 

<div align="center">
  <!-- CI -->
  <img src="https://github.com/sunli829/potatonet/workflows/CI/badge.svg" />
  <!-- codecov -->
  <img src="https://codecov.io/gh/sunli829/async-graphql/branch/master/graph/badge.svg" />
  <!-- Crates version -->
  <a href="https://crates.io/crates/async-graphql">
    <img src="https://img.shields.io/crates/v/async-graphql.svg?style=flat-square"
    alt="Crates.io version" />
  </a>
  <!-- Downloads -->
  <a href="https://crates.io/crates/async-graphql">
    <img src="https://img.shields.io/crates/d/async-graphql.svg?style=flat-square"
      alt="Download" />
  </a>
  <!-- docs.rs docs -->
  <a href="https://docs.rs/async-graphql">
    <img src="https://img.shields.io/badge/docs-latest-blue.svg?style=flat-square"
      alt="docs.rs docs" />
  </a>
</div>

`async-graphql` is a GraphQL server library that fully supports async/await and is easy to use.

It supports all of the GraphQL specifications and is easy to integrate into existing web servers.

* [Docs](https://docs.rs/async-graphql)
* [GitHub repository](https://github.com/sunli829/async-graphql)
* [Cargo package](https://crates.io/crates/async-graphql)
* Minimum supported Rust version: 1.42 or later

## Examples

https://github.com/sunli829/async-graphql-examples

## Benchmark

```shell script
git clone https://github.com/sunli829/graphql-benchmark
cargo run --release
```

## Features

* Fully support async/await
* Type safety
* Rustfmt friendly (Procedural Macro)
* Custom scalar
* Minimal overhead
* Easy integration (hyper, actix_web, tide ...)
* Upload files (Multipart request)
* Subscription (WebSocket transport)
* Custom extension
* Apollo Tracing extension
* Limit query complexity/depth
* Error Extensions
* Apollo Federation

## Integrations

* Actix-web [async-graphql-actix-web](https://crates.io/crates/async-graphql-actix-web)
* Warp [async-graphql-warp](https://crates.io/crates/async-graphql-warp)

## License

Licensed under either of

* Apache License, Version 2.0,
  (./LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license (./LICENSE-MIT or http://opensource.org/licenses/MIT)
  at your option.

## References

* [GraphQL](https://graphql.org)
* [GraphQL Multipart Request](https://github.com/jaydenseric/graphql-multipart-request-spec)
* [GraphQL Cursor Connections Specification](https://facebook.github.io/relay/graphql/connections.htm)
* [GraphQL over WebSocket Protocol](https://github.com/apollographql/subscriptions-transport-ws/blob/master/PROTOCOL.md)
* [Apollo Tracing](https://github.com/apollographql/apollo-tracing)
* [Apollo Federation](https://www.apollographql.com/docs/apollo-server/federation/introduction)

## Contribute

Welcome to contribute !