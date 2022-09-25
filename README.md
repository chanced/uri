# uri

[![Go Reference](https://pkg.go.dev/badge/github.com/chanced/uri.svg)](https://pkg.go.dev/github.com/chanced/uri)
[![Latest Version](https://img.shields.io/github/v/tag/chanced/uri.svg?sort=semver&style=flat-square&label=version&color=blue)](https://img.shields.io/github/v/tag/chanced/uri.svg?sort=semver&style=flat-square&label=version&color=blue)
![Build Status](https://img.shields.io/github/workflow/status/chanced/uri/Build?style=flat-square)

uri is a copy of net/url 1.19 except `URI` implements `encoding.TextUnmarshaler` and `encoding.TextMarshaler`.

Another notable change:

If `URI` is empty, the `String` method returns `"#"` rather than an empty string.

## License

Go License
