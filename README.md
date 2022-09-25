# uri

[![Go Reference](https://pkg.go.dev/badge/github.com/chanced/uri.svg)](https://pkg.go.dev/github.com/chanced/uri)
[![Latest Version](https://img.shields.io/github/v/tag/chanced/uri.svg?sort=semver&style=flat-square&label=version&color=blue)](https://img.shields.io/github/v/tag/chanced/uri.svg?sort=semver&style=flat-square&label=version&color=blue)
![Build Status](https://img.shields.io/github/workflow/status/chanced/uri/Build?style=flat-square)

uri is a wrapper around net/url where `uri.URI` (newtype of `url.URL`) implements `encoding.TextUnmarshaler` and `encoding.TextMarshaler`.

Another notable change:

If empty, `String` returns `"#"` rather than an empty string.

## License

Apache 2.0
