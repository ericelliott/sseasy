- **v2.0.1 Bugfix**. Removes stray console.log.

- **v2.0.0 Breaking change**. `res.sse` is now a writeable stream. Use `res.sse.write` to write individual SSE events.
