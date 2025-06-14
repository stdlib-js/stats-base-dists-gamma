# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-06-09)

<section class="features">

### Features

-   [`5c47b95`](https://github.com/stdlib-js/stdlib/commit/5c47b95b984cb0e088f642974e05ae9d7d6bffa0) - add C implementation `stats/base/dists/gamma/logpdf` [(#4800)](https://github.com/stdlib-js/stdlib/pull/4800)
-   [`d9a9405`](https://github.com/stdlib-js/stdlib/commit/d9a940585dd1beedc9a197abbe19943e8233f941) - add C implementation for `stats/base/dists/gamma/variance` [(#3944)](https://github.com/stdlib-js/stdlib/pull/3944)
-   [`a4cc596`](https://github.com/stdlib-js/stdlib/commit/a4cc596f9cdd579bad8e486f1feee2200f23ea9e) - add C implementation for `stats/base/dists/gamma/mgf` [(#4354)](https://github.com/stdlib-js/stdlib/pull/4354)
-   [`78c8b3c`](https://github.com/stdlib-js/stdlib/commit/78c8b3cd1b7116442b4fc0106cf4f6aec5bb0e51) - add C implementation for `stats/base/dists/gamma/entropy` [(#4349)](https://github.com/stdlib-js/stdlib/pull/4349)
-   [`83aeb94`](https://github.com/stdlib-js/stdlib/commit/83aeb942ded7a90ee0b954fedc683f7b46ddd5e7) - add C implementation for `stats/base/dists/gamma/stdev` [(#4128)](https://github.com/stdlib-js/stdlib/pull/4128)
-   [`6043777`](https://github.com/stdlib-js/stdlib/commit/6043777df454d2e288e0f00ebe7cbc3b26423c1b) - add C implementation for `stats/base/dists/gamma/skewness` [(#4124)](https://github.com/stdlib-js/stdlib/pull/4124)
-   [`8e65742`](https://github.com/stdlib-js/stdlib/commit/8e65742b7b96655c166c7fc11d2399d7ca2bad01) - add C implementation for `stats/base/dists/gamma/mode` [(#4123)](https://github.com/stdlib-js/stdlib/pull/4123)
-   [`cf1fd6a`](https://github.com/stdlib-js/stdlib/commit/cf1fd6a5a6e83c345aa5ad0ff830c0cbbfa3a15d) - add C implementation for `stats/base/dists/gamma/kurtosis` [(#4129)](https://github.com/stdlib-js/stdlib/pull/4129)
-   [`8627f7a`](https://github.com/stdlib-js/stdlib/commit/8627f7a099aeb10863e83e4a1005dc4749b5d371) - add C implementation for `stats/base/dists/gamma/mean` [(#4122)](https://github.com/stdlib-js/stdlib/pull/4122)

</section>

<!-- /.features -->

<section class="issues">

### Closed Issues

A total of 10 issues were closed in this release:

[#3618](https://github.com/stdlib-js/stdlib/issues/3618), [#3619](https://github.com/stdlib-js/stdlib/issues/3619), [#3621](https://github.com/stdlib-js/stdlib/issues/3621), [#3622](https://github.com/stdlib-js/stdlib/issues/3622), [#3623](https://github.com/stdlib-js/stdlib/issues/3623), [#3624](https://github.com/stdlib-js/stdlib/issues/3624), [#3627](https://github.com/stdlib-js/stdlib/issues/3627), [#3628](https://github.com/stdlib-js/stdlib/issues/3628), [#3629](https://github.com/stdlib-js/stdlib/issues/3629), [#5143](https://github.com/stdlib-js/stdlib/issues/5143)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`3565318`](https://github.com/stdlib-js/stdlib/commit/3565318e3639b3e44890ed15ccd73560d3cac14c) - **refactor:** update paths _(by Gururaj Gurram)_
-   [`5f73301`](https://github.com/stdlib-js/stdlib/commit/5f73301a8509cc423a06b02140c4e316fd02ff49) - **docs:** minor clean-up _(by Philipp Burckhardt)_
-   [`8f66d56`](https://github.com/stdlib-js/stdlib/commit/8f66d56a08779f053154777f958a7e18bd02187b) - **bench:** fix indentation and remove stray 0 _(by Philipp Burckhardt)_
-   [`5c47b95`](https://github.com/stdlib-js/stdlib/commit/5c47b95b984cb0e088f642974e05ae9d7d6bffa0) - **feat:** add C implementation `stats/base/dists/gamma/logpdf` [(#4800)](https://github.com/stdlib-js/stdlib/pull/4800) _(by Shabareesh Shetty, Philipp Burckhardt, stdlib-bot)_
-   [`e403884`](https://github.com/stdlib-js/stdlib/commit/e403884f1b3ac0a4bc7d0b3bc954e69273bba891) - **bench:** ensure NaN is not possible _(by Athan Reines)_
-   [`d9a9405`](https://github.com/stdlib-js/stdlib/commit/d9a940585dd1beedc9a197abbe19943e8233f941) - **feat:** add C implementation for `stats/base/dists/gamma/variance` [(#3944)](https://github.com/stdlib-js/stdlib/pull/3944) _(by Aayush Khanna, Philipp Burckhardt, stdlib-bot)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`f7988d3`](https://github.com/stdlib-js/stdlib/commit/f7988d3c02e0eff3bd9bd7523b5dc975bb98dc0e) - **bench:** fix `isnan` checks in `stats/base/dists` [(#5296)](https://github.com/stdlib-js/stdlib/pull/5296) _(by Karan Anand)_
-   [`9d153b5`](https://github.com/stdlib-js/stdlib/commit/9d153b57100822ae6fe4cd3ad9475bf3ee4c8200) - **bench:** remove duplicate logic [(#5160)](https://github.com/stdlib-js/stdlib/pull/5160) _(by ekambains)_
-   [`e61b1de`](https://github.com/stdlib-js/stdlib/commit/e61b1dee3334bacf30d213de5b5f1c7868c0753b) - **docs:** clean-up of C docstrings _(by Philipp Burckhardt)_
-   [`b9a2014`](https://github.com/stdlib-js/stdlib/commit/b9a2014b1181d30f86aa489ba90ad1f892ade8e8) - **docs:** clean-up of C docstrings _(by Philipp Burckhardt)_
-   [`c7860af`](https://github.com/stdlib-js/stdlib/commit/c7860af1896d84360294b65f3e37982ca631c435) - **bench:** refactor random number generation in `stats/base/dists/gamma` [(#4929)](https://github.com/stdlib-js/stdlib/pull/4929) _(by Karan Anand)_
-   [`a4cc596`](https://github.com/stdlib-js/stdlib/commit/a4cc596f9cdd579bad8e486f1feee2200f23ea9e) - **feat:** add C implementation for `stats/base/dists/gamma/mgf` [(#4354)](https://github.com/stdlib-js/stdlib/pull/4354) _(by Neeraj Pathak, Philipp Burckhardt, stdlib-bot)_
-   [`78c8b3c`](https://github.com/stdlib-js/stdlib/commit/78c8b3cd1b7116442b4fc0106cf4f6aec5bb0e51) - **feat:** add C implementation for `stats/base/dists/gamma/entropy` [(#4349)](https://github.com/stdlib-js/stdlib/pull/4349) _(by Neeraj Pathak, Philipp Burckhardt, stdlib-bot)_
-   [`f75a0ce`](https://github.com/stdlib-js/stdlib/commit/f75a0cef6a3112b166dba04c13bada9763cec350) - **chore:** use excess kurtosis consistently _(by Philipp Burckhardt)_
-   [`f3df15f`](https://github.com/stdlib-js/stdlib/commit/f3df15f118d563573f27d2d2b96e35b842f05a18) - **chore:** directly draw from the desired distribution instead of adding constants _(by Philipp Burckhardt)_
-   [`fc0ff17`](https://github.com/stdlib-js/stdlib/commit/fc0ff171dab59e73e1748c1bff504166adc826c3) - **chore:** directly draw from the desired distribution instead of adding constants _(by Philipp Burckhardt)_
-   [`b7867cb`](https://github.com/stdlib-js/stdlib/commit/b7867cbb3a4fc453e19203794402c36f19b264fd) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`83aeb94`](https://github.com/stdlib-js/stdlib/commit/83aeb942ded7a90ee0b954fedc683f7b46ddd5e7) - **feat:** add C implementation for `stats/base/dists/gamma/stdev` [(#4128)](https://github.com/stdlib-js/stdlib/pull/4128) _(by Prashant Kumar Yadav, Philipp Burckhardt)_
-   [`6043777`](https://github.com/stdlib-js/stdlib/commit/6043777df454d2e288e0f00ebe7cbc3b26423c1b) - **feat:** add C implementation for `stats/base/dists/gamma/skewness` [(#4124)](https://github.com/stdlib-js/stdlib/pull/4124) _(by Prashant Kumar Yadav, Philipp Burckhardt)_
-   [`8e65742`](https://github.com/stdlib-js/stdlib/commit/8e65742b7b96655c166c7fc11d2399d7ca2bad01) - **feat:** add C implementation for `stats/base/dists/gamma/mode` [(#4123)](https://github.com/stdlib-js/stdlib/pull/4123) _(by Prashant Kumar Yadav, Philipp Burckhardt)_
-   [`cf1fd6a`](https://github.com/stdlib-js/stdlib/commit/cf1fd6a5a6e83c345aa5ad0ff830c0cbbfa3a15d) - **feat:** add C implementation for `stats/base/dists/gamma/kurtosis` [(#4129)](https://github.com/stdlib-js/stdlib/pull/4129) _(by Prashant Kumar Yadav)_
-   [`8627f7a`](https://github.com/stdlib-js/stdlib/commit/8627f7a099aeb10863e83e4a1005dc4749b5d371) - **feat:** add C implementation for `stats/base/dists/gamma/mean` [(#4122)](https://github.com/stdlib-js/stdlib/pull/4122) _(by Prashant Kumar Yadav)_
-   [`fdd3963`](https://github.com/stdlib-js/stdlib/commit/fdd3963096904e999191e354dede1ca59461adc2) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`e399bfd`](https://github.com/stdlib-js/stdlib/commit/e399bfd09baf0b50ea9beb49f65867cd1a1e45b7) - **docs:** improve README examples of `stats/base/dists/gamma` namespace [(#1804)](https://github.com/stdlib-js/stdlib/pull/1804) _(by Shivam Ahir, Philipp Burckhardt, shivam Ahir)_
-   [`f387603`](https://github.com/stdlib-js/stdlib/commit/f387603e739f88a38af3263ce6ff675ad903ee8c) - **docs:** consistently use declarative instead of imperative sentences outside of intros _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 10 people contributed to this release. Thank you to the following contributors:

-   Aayush Khanna
-   Athan Reines
-   Gururaj Gurram
-   Karan Anand
-   Neeraj Pathak
-   Philipp Burckhardt
-   Prashant Kumar Yadav
-   Shabareesh Shetty
-   Shivam Ahir
-   ekambains

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.2">

## 0.2.2 (2024-07-28)

<section class="commits">

### Commits

<details>

-   [`41d41e9`](https://github.com/stdlib-js/stdlib/commit/41d41e959b4eaad3c631e6898e3144a4015a5458) - **test:** include trailing newlines in Julia-generated JSON fixtures _(by Philipp Burckhardt)_
-   [`9ed7d0e`](https://github.com/stdlib-js/stdlib/commit/9ed7d0e7d57edb5ad0dfb65c944bed87d475cbf3) - **chore:** add missing trailing newlines _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-24)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

<section class="commits">

### Commits

<details>

-   [`9502ed2`](https://github.com/stdlib-js/stdlib/commit/9502ed27e2853e312c556a48bdd7775095e66709) - **build:** replace tslint directive with eslint equivalent _(by Philipp Burckhardt)_
-   [`d73bbf4`](https://github.com/stdlib-js/stdlib/commit/d73bbf43d222f935085f8ecf7526e5f57835f74e) - **build:** replace lint directives _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-24)

<section class="features">

### Features

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - **feat:** update minimum TypeScript version _(by Philipp Burckhardt)_
-   [`d5fa8e8`](https://github.com/stdlib-js/stdlib/commit/d5fa8e8a6267a837a25a7027e9fe3e847bc2d1c5) - **test:** use strictEqual checks _(by Philipp Burckhardt)_
-   [`ce7e336`](https://github.com/stdlib-js/stdlib/commit/ce7e3367c0f9477773fe76dd0eca64dc6ad33c02) - **docs:** update equations _(by Philipp Burckhardt)_
-   [`37f032d`](https://github.com/stdlib-js/stdlib/commit/37f032d4a571f667ea99f6f52f60b5d736c627f3) - **docs:** render equations via math code blocks _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2022-07-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2022-02-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-07-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-27)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.1">

## 0.0.1 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

