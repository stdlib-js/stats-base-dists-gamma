<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Gamma

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Gamma distribution.



<section class="usage">

## Usage

To use in Observable,

```javascript
gamma = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma@umd/browser.js' )
```
The previous example will load the latest bundled code from the umd branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/stats-base-dists-gamma/tags). For example,

```javascript
gamma = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma@v0.1.0-umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var gamma = require( 'path/to/vendor/umd/stats-base-dists-gamma/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.gamma;
})();
</script>
```

#### gamma

Gamma distribution.

```javascript
var dist = gamma;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pdf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, alpha, beta )`][@stdlib/stats/base/dists/gamma/cdf]</span><span class="delimiter">: </span><span class="description">gamma distribution cumulative distribution function.</span>
-   <span class="signature">[`logcdf( x, alpha, beta )`][@stdlib/stats/base/dists/gamma/logcdf]</span><span class="delimiter">: </span><span class="description">gamma distribution logarithm of cumulative distribution function (CDF).</span>
-   <span class="signature">[`logpdf( x, alpha, beta )`][@stdlib/stats/base/dists/gamma/logpdf]</span><span class="delimiter">: </span><span class="description">gamma distribution logarithm of probability density function (PDF).</span>
-   <span class="signature">[`mgf( t, alpha, beta )`][@stdlib/stats/base/dists/gamma/mgf]</span><span class="delimiter">: </span><span class="description">gamma distribution moment-generating function (MGF).</span>
-   <span class="signature">[`pdf( x, alpha, beta )`][@stdlib/stats/base/dists/gamma/pdf]</span><span class="delimiter">: </span><span class="description">gamma distribution probability density function (PDF).</span>
-   <span class="signature">[`quantile( p, alpha, beta )`][@stdlib/stats/base/dists/gamma/quantile]</span><span class="delimiter">: </span><span class="description">gamma distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`entropy( alpha, beta )`][@stdlib/stats/base/dists/gamma/entropy]</span><span class="delimiter">: </span><span class="description">gamma distribution differential entropy.</span>
-   <span class="signature">[`kurtosis( alpha, beta )`][@stdlib/stats/base/dists/gamma/kurtosis]</span><span class="delimiter">: </span><span class="description">gamma distribution excess kurtosis.</span>
-   <span class="signature">[`mean( alpha, beta )`][@stdlib/stats/base/dists/gamma/mean]</span><span class="delimiter">: </span><span class="description">gamma distribution expected value.</span>
-   <span class="signature">[`mode( alpha, beta )`][@stdlib/stats/base/dists/gamma/mode]</span><span class="delimiter">: </span><span class="description">gamma distribution mode.</span>
-   <span class="signature">[`skewness( alpha, beta )`][@stdlib/stats/base/dists/gamma/skewness]</span><span class="delimiter">: </span><span class="description">gamma distribution skewness.</span>
-   <span class="signature">[`stdev( alpha, beta )`][@stdlib/stats/base/dists/gamma/stdev]</span><span class="delimiter">: </span><span class="description">gamma distribution standard deviation.</span>
-   <span class="signature">[`variance( alpha, beta )`][@stdlib/stats/base/dists/gamma/variance]</span><span class="delimiter">: </span><span class="description">gamma distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [gamma][gamma-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`Gamma( [alpha, beta] )`][@stdlib/stats/base/dists/gamma/ctor]</span><span class="delimiter">: </span><span class="description">gamma distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var Gamma = require( '@stdlib/stats-base-dists-gamma' ).Gamma;

var dist = new Gamma( 2.0, 4.0 );

var y = dist.cdf( 0.5 );
// returns ~0.594
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma@umd/browser.js"></script>
<script type="text/javascript">
(function () {

console.log( objectKeys( gamma ) );

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-gamma.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-gamma

[test-image]: https://github.com/stdlib-js/stats-base-dists-gamma/actions/workflows/test.yml/badge.svg?branch=v0.1.0
[test-url]: https://github.com/stdlib-js/stats-base-dists-gamma/actions/workflows/test.yml?query=branch:v0.1.0

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-gamma/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-gamma?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-gamma.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-gamma/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-gamma/tree/deno
[umd-url]: https://github.com/stdlib-js/stats-base-dists-gamma/tree/umd
[esm-url]: https://github.com/stdlib-js/stats-base-dists-gamma/tree/esm
[branches-url]: https://github.com/stdlib-js/stats-base-dists-gamma/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-gamma/main/LICENSE

[gamma-distribution]: https://en.wikipedia.org/wiki/Gamma_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/gamma/ctor]: https://github.com/stdlib-js/stats-base-dists-gamma-ctor/tree/umd

[@stdlib/stats/base/dists/gamma/entropy]: https://github.com/stdlib-js/stats-base-dists-gamma-entropy/tree/umd

[@stdlib/stats/base/dists/gamma/kurtosis]: https://github.com/stdlib-js/stats-base-dists-gamma-kurtosis/tree/umd

[@stdlib/stats/base/dists/gamma/mean]: https://github.com/stdlib-js/stats-base-dists-gamma-mean/tree/umd

[@stdlib/stats/base/dists/gamma/mode]: https://github.com/stdlib-js/stats-base-dists-gamma-mode/tree/umd

[@stdlib/stats/base/dists/gamma/skewness]: https://github.com/stdlib-js/stats-base-dists-gamma-skewness/tree/umd

[@stdlib/stats/base/dists/gamma/stdev]: https://github.com/stdlib-js/stats-base-dists-gamma-stdev/tree/umd

[@stdlib/stats/base/dists/gamma/variance]: https://github.com/stdlib-js/stats-base-dists-gamma-variance/tree/umd

[@stdlib/stats/base/dists/gamma/cdf]: https://github.com/stdlib-js/stats-base-dists-gamma-cdf/tree/umd

[@stdlib/stats/base/dists/gamma/logcdf]: https://github.com/stdlib-js/stats-base-dists-gamma-logcdf/tree/umd

[@stdlib/stats/base/dists/gamma/logpdf]: https://github.com/stdlib-js/stats-base-dists-gamma-logpdf/tree/umd

[@stdlib/stats/base/dists/gamma/mgf]: https://github.com/stdlib-js/stats-base-dists-gamma-mgf/tree/umd

[@stdlib/stats/base/dists/gamma/pdf]: https://github.com/stdlib-js/stats-base-dists-gamma-pdf/tree/umd

[@stdlib/stats/base/dists/gamma/quantile]: https://github.com/stdlib-js/stats-base-dists-gamma-quantile/tree/umd

<!-- </toc-links> -->

</section>

<!-- /.links -->
