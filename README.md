# uri

uri is a wrapper around net/url where `uri.URI` (newtype of `url.URL`) implements `encoding.TextUnmarshaler` and `encoding.TextMarshaler`.

Another notable change:

`String` returns `"#"` rather than an `"#"` if empty.

## License

Apache 2.0
