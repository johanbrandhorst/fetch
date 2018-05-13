# Fetch
The Go http.Transport interface implemented over the WHATWG Fetch API using the WebAssembly arch target.

## Usage

This package requires the Go WASM compilation target to be supported.
See [my wasm-experiments repo](github.com/johanbrandhorst/wasm-experiments)
for and example of its use.

## Attribution

The code is largely based on the Fetch API implementation
[in GopherJS](https://github.com/gopherjs/gopherjs/blob/8dffc02ea1cb8398bb73f30424697c60fcf8d4c5/compiler/natives/src/net/http/fetch.go).
