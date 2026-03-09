# std-semver

[![Open on npmx][npmx-version-src]][npmx-href]
[![npm downloads][npmx-downloads-src]][npmx-href]
[![Test Build][test-build-src]][test-build-href]

npm port of [@std/semver](https://jsr.io/@std/semver).

## Install

```bash
npm i std-semver
```

## Usage

```ts
import { format, greaterThan, lessThan, parse, parseRange } from 'std-semver'

const semver = parse('1.2.3')
const range = parseRange('1.x || >=2.5.0 || 5.0.0 - 7.2.3')
const s0 = parse('1.2.3')
const s1 = parse('9.8.7')
```

More APIs and details can be found in the [original `@std/semver`](https://jsr.io/@std/semver).

## License

[MIT](./LICENSE) License © 2026-PRESENT [Kevin Deng](https://github.com/sxzz)

Copyright 2018-2026 the Deno authors. MIT license.

<!-- Badges -->

[npmx-version-src]: https://npmx.dev/api/registry/badge/version/std-semver
[npmx-downloads-src]: https://npmx.dev/api/registry/badge/downloads-month/std-semver
[npmx-href]: https://npmx.dev/package/std-semver
[test-build-src]: https://github.com/sxzz/std-semver/actions/workflows/test-build.yml/badge.svg
[test-build-href]: https://github.com/sxzz/std-semver/actions/workflows/test-build.yml
