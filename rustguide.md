# Rust Style Guide

## Compiler

It is recommended to use the latest [Rust container](https://registry.hub.docker.com/u/cosmosio/rust/) to build your projects. Of course you can install [Rust](http://www.rust-lang.org) directly on yours but it is recommended to build your projects with the latest [Rust container](https://registry.hub.docker.com/u/cosmosio/rust/) for the below some reasons.

* Rust is very unstable.
* We need to build same projects on the same Rust compiler.

When you build source code with [Rust container](https://registry.hub.docker.com/u/cosmosio/rust/):

```
docker run --rm -it -v $(pwd):/source cosmosio/rust
```

When you build Curiosity, you need to get docker.sock:

```
docker run --rm -it -v $(pwd):/source -v /var/run/docker.sock:/var/run/docker.sock cosmosio/rust
```