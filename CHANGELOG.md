# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2022-06-29

- Added `namespace: loki` to [values.yaml](chart/values.yaml) as required by [Karavel CLI 0.4](https://github.com/karavel-io/cli/releases/tag/v0.4.0)
- Updated loki to [v2.5.0](https://github.com/grafana/loki/releases/tag/v2.5.0)

## [1.0.1] - 2022-03-28

### Changed

- Switch from the official `docker.io/grafana/loki` and `docker.io/grafana/promtail` image to the vendored `quay.io/karavel/loki` and `quay.io/karavel/promtail` to avoid Docker Hub's rate limits.

## [1.0.0] - 2022-03-22

Initial release

[unreleased]: https://github.com/karavel-io/platform-component-loki/compare/1.1.0...HEAD
[1.1.0]: https://github.com/karavel-io/platform-component-loki/compare/1.0.1...1.1.0
[1.0.1]: https://github.com/karavel-io/platform-component-loki/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/karavel-io/platform-component-loki/releases/tag/1.0.0
