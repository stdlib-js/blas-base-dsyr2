# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-06-24)

<section class="bug-fixes">

### Bug Fixes

-   [`95a8c41`](https://github.com/stdlib-js/stdlib/commit/95a8c41a2a5313aea289e722bed88bc888454233) - use correct argument value in error message and propagate JSDoc fixes to sibling packages [(#12302)](https://github.com/stdlib-js/stdlib/pull/12302)

</section>

<!-- /.bug-fixes -->

<section class="issues">

### Closed Issues

This release closes the following issue:

[#10285](https://github.com/stdlib-js/stdlib/issues/10285)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`95a8c41`](https://github.com/stdlib-js/stdlib/commit/95a8c41a2a5313aea289e722bed88bc888454233) - **fix:** use correct argument value in error message and propagate JSDoc fixes to sibling packages [(#12302)](https://github.com/stdlib-js/stdlib/pull/12302) _(by Philipp Burckhardt)_
-   [`39db70f`](https://github.com/stdlib-js/stdlib/commit/39db70f0446038735b98e82abc26b369ac34938f) - **bench:** refactor to use string interpolation in `@stdlib/blas` [(#11397)](https:-/github.com/stdlib-js/stdlib/pull/11397) _(by Karan Anand)_
-   [`d7c9e82`](https://github.com/stdlib-js/stdlib/commit/d7c9e8257ce6c5eead817a24a26556c3efb62cf8) - **test:** remove empty line between require statements in `test.dsyr2.js` [(#10288)](https://github.com/stdlib-js/stdlib/pull/10288) _(by Lakshmi Sravya Vedantham, lakshmisravya123)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 4 people contributed to this release. Thank you to the following contributors:

-   Karan Anand
-   Lakshmi Sravya Vedantham
-   Philipp Burckhardt
-   lakshmisravya123

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.1">

## 0.1.1 (2026-02-08)

<section class="features">

### Features

-   [`75e2622`](https://github.com/stdlib-js/stdlib/commit/75e2622f2a9c4a5f7b6fc639dcabe3129d9f6ca9) - add C implementation for `blas/base/dsyr2` [(#6572)](https://github.com/stdlib-js/stdlib/pull/6572)
-   [`6966bbb`](https://github.com/stdlib-js/stdlib/commit/6966bbb8dcfdc2345fe3fb04c2100c6a313d3282) - add `blas/base/dsyr2` [(#2712)](https://github.com/stdlib-js/stdlib/pull/2712)

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`15d72a1`](https://github.com/stdlib-js/stdlib/commit/15d72a11d2c316d6e07e667eea6a8ca69156dfd1) - update error messages and fix parameter name
-   [`785bc4c`](https://github.com/stdlib-js/stdlib/commit/785bc4c84dee00021ec5f0bad034bf99603ba5cb) - use correct stride in error message
-   [`e20f4e4`](https://github.com/stdlib-js/stdlib/commit/e20f4e4af09a7608b4f7ebeff0f8050295c646d9) - condition check in `blas/base/dsyr2` ndarray [(#6532)](https://github.com/stdlib-js/stdlib/pull/6532)

</section>

<!-- /.bug-fixes -->

<section class="commits">

### Commits

<details>

-   [`a4c852e`](https://github.com/stdlib-js/stdlib/commit/a4c852e7b5f111798b4c85218e94b293d1c96b65) - **bench:** refactor to use dynamic memory allocation [(#9213)](https://github.com/stdlib-js/stdlib/pull/9213) _(by Samarth Kolarkar)_
-   [`7e39b69`](https://github.com/stdlib-js/stdlib/commit/7e39b69431dfad9f542cd3b8028d4bd50718fc24) - **docs:** fix TSDoc return annotation values and example code _(by Philipp Burckhardt)_
-   [`15d72a1`](https://github.com/stdlib-js/stdlib/commit/15d72a11d2c316d6e07e667eea6a8ca69156dfd1) - **fix:** update error messages and fix parameter name _(by Athan Reines)_
-   [`11f3cfa`](https://github.com/stdlib-js/stdlib/commit/11f3cfa5a658d7cb105aeb2578b7d72ea62f1e97) - **refactor:** update include header guards for double precision real packages [(#7711)](https://github.com/stdlib-js/stdlib/pull/7711) _(by Shabareesh Shetty)_
-   [`785bc4c`](https://github.com/stdlib-js/stdlib/commit/785bc4c84dee00021ec5f0bad034bf99603ba5cb) - **fix:** use correct stride in error message _(by Philipp Burckhardt)_
-   [`75e2622`](https://github.com/stdlib-js/stdlib/commit/75e2622f2a9c4a5f7b6fc639dcabe3129d9f6ca9) - **feat:** add C implementation for `blas/base/dsyr2` [(#6572)](https://github.com/stdlib-js/stdlib/pull/6572) _(by Shabareesh Shetty, Athan Reines, stdlib-bot, Aman Bhansali)_
-   [`d135424`](https://github.com/stdlib-js/stdlib/commit/d135424ecc329f4c64726d2ff57ea9ac511275f6) - **test:** add test cases for `blas/base/dsyr2` [(#7132)](https://github.com/stdlib-js/stdlib/pull/7132) _(by Shabareesh Shetty, Athan Reines)_
-   [`62f4456`](https://github.com/stdlib-js/stdlib/commit/62f44566136dc483daf350847f016c63c714b530) - **refactor:** use base assertion utility _(by Athan Reines)_
-   [`b25755a`](https://github.com/stdlib-js/stdlib/commit/b25755aec061fdb02888f6e1cb400cec6aae8293) - **test:** add test cases for `blas/base/dsyr2` [(#6731)](https://github.com/stdlib-js/stdlib/pull/6731) _(by Shabareesh Shetty)_
-   [`58a8f55`](https://github.com/stdlib-js/stdlib/commit/58a8f55ac6713976035ec7834012ae74455aa603) - **test:** increase code coverage in `blas/base/dsyr2` [(#6546)](https://github.com/stdlib-js/stdlib/pull/6546) _(by Shabareesh Shetty, Athan Reines, stdlib-bot)_
-   [`e20f4e4`](https://github.com/stdlib-js/stdlib/commit/e20f4e4af09a7608b4f7ebeff0f8050295c646d9) - **fix:** condition check in `blas/base/dsyr2` ndarray [(#6532)](https://github.com/stdlib-js/stdlib/pull/6532) _(by Shabareesh Shetty)_
-   [`4ca068f`](https://github.com/stdlib-js/stdlib/commit/4ca068f174225d1eaec123656682589febf1b547) - **test:** update to test for exact equality [(#2864)](https://github.com/stdlib-js/stdlib/pull/2864) _(by Aman Bhansali)_
-   [`e0cef99`](https://github.com/stdlib-js/stdlib/commit/e0cef995e884021db3001dc1a3cfef0ca7b368c2) - **style:** remove extra spaces for regular expressions in publish script _(by Philipp Burckhardt)_
-   [`6966bbb`](https://github.com/stdlib-js/stdlib/commit/6966bbb8dcfdc2345fe3fb04c2100c6a313d3282) - **feat:** add `blas/base/dsyr2` [(#2712)](https://github.com/stdlib-js/stdlib/pull/2712) _(by Aman Bhansali, Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 5 people contributed to this release. Thank you to the following contributors:

-   Aman Bhansali
-   Athan Reines
-   Philipp Burckhardt
-   Samarth Kolarkar
-   Shabareesh Shetty

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

