# @net/http-body — Streaming HTTP Body Trait for Zeta

Zeta port of the [hyperium/http-body](https://github.com/hyperium/http-body) library (v1.0.1).

## Features

- `Body` trait for streaming HTTP request/response bodies
- `Frame<Data>` — individual data or trailers frame
- `SizeHint` — bounds on remaining body length

## Types

- `Body` trait — poll_frame, is_end_stream, size_hint
- `Frame<T>` — data or trailers frame
- `SizeHint` — lower/upper size bounds

## License

MIT
