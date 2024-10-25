# http-echo-rs

This is a simple echo server for HTTP. It is useful for debugging purposes.

## Usage

It uses `env_logger` for tracing. You can add HTTP headers to the response using the `-H` flag.

```bash
RUST_LOG=debug cargo run -- -H "debug: true" 
```
