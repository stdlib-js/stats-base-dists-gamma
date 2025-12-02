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

```javascript
import gamma from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma@esm/index.mjs';
```

You can also import the following named exports from the package:

```javascript
import { Gamma, cdf, entropy, kurtosis, logcdf, logpdf, mean, mgf, mode, pdf, quantile, skewness, stdev, variance } from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma@esm/index.mjs';
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
var Gamma = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma' ).Gamma;

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
<script type="module">

var gammaRandomFactory = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/random-base-gamma' ).factory;
import filledarrayby from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-filled-by@esm/index.mjs';
import Float64Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-float64@esm/index.mjs';
import variance from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-strided-variance@esm/index.mjs';
import linspace from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-base-linspace@esm/index.mjs';
import mean from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-strided-mean@esm/index.mjs';
import abs from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-abs@esm/index.mjs';
import gamma from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-gamma@esm/index.mjs';

// Define the shape and scale parameters:
var alpha = 3.0; // shape parameter (α)
var beta = 2.0;  // scale parameter (β)

// Generate an array of x values:
var x = linspace( 0.0, 20.0, 100 );

// Compute the PDF for each x:
var gammaPDF = gamma.pdf.factory( alpha, beta );
var pdf = filledarrayby( x.length, 'float64', gammaPDF );

// Compute the CDF for each x:
var gammaCDF = gamma.cdf.factory( alpha, beta );
var cdf = filledarrayby( x.length, 'float64', gammaCDF );

// Output the PDF and CDF values:
console.log( 'x values: %s', x );
console.log( 'PDF values: %s', pdf );
console.log( 'CDF values: %s', cdf );

// Compute statistical properties:
var theoreticalMean = gamma.mean( alpha, beta );
var theoreticalVariance = gamma.variance( alpha, beta );
var theoreticalSkewness = gamma.skewness( alpha, beta );
var theoreticalKurtosis = gamma.kurtosis( alpha, beta );

console.log( 'Theoretical Mean: %s', theoreticalMean );
console.log( 'Theoretical Variance: %s', theoreticalVariance );
console.log( 'Skewness: %s', theoreticalSkewness );
console.log( 'Kurtosis: %s', theoreticalKurtosis );

// Generate random samples from the gamma distribution:
var rgamma = gammaRandomFactory( alpha, beta );
var n = 300;
var samples = filledarrayby( n, 'float64', rgamma );

// Compute sample mean and variance:
var sampleMean = mean( n, samples, 1 );
var sampleVariance = variance( n, 1, samples, 1 );

console.log( 'Sample Mean: %s', sampleMean );
console.log( 'Sample Variance: %s', sampleVariance );

// Compare sample statistics to theoretical values:
console.log( 'Difference in Mean: %s', abs( theoreticalMean - sampleMean ) );
console.log( 'Difference in Variance: %s', abs( theoreticalVariance - sampleVariance ) );

// Demonstrate that the sum of `k` gamma variables is a gamma-distributed sum of `k` gamma(α, β) variables with same β is `gamma(k*α, β)`:
var k = 5;
var sumSamples = new Float64Array( n );

var sum;
var i;
var j;
for ( i = 0; i < sumSamples.length; i++ ) {
    sum = 0.0;
    for ( j = 0; j < k; j++ ) {
        sum += rgamma();
    }
    sumSamples[ i ] = sum;
}

// Theoretical parameters for the sum:
var sumAlpha = k * alpha;
var sumMean = gamma.mean( sumAlpha, beta );
var sumVariance = gamma.variance( sumAlpha, beta );

console.log( 'Sum Theoretical Mean: %s', sumMean );
console.log( 'Sum Theoretical Variance: %s', sumVariance );

// Compute sample mean and variance for the sum:
var sumSampleMean = mean( sumSamples.length, sumSamples, 1 );
var sumSampleVariance = variance( sumSamples.length, 1, sumSamples, 1 );

console.log( 'Sum Sample Mean: %s', sumSampleMean );
console.log( 'Sum Sample Variance: %s', sumSampleVariance );

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

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2025. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-gamma.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-gamma

[test-image]: https://github.com/stdlib-js/stats-base-dists-gamma/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/stats-base-dists-gamma/actions/workflows/test.yml?query=branch:main

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
[deno-readme]: https://github.com/stdlib-js/stats-base-dists-gamma/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/stats-base-dists-gamma/tree/umd
[umd-readme]: https://github.com/stdlib-js/stats-base-dists-gamma/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/stats-base-dists-gamma/tree/esm
[esm-readme]: https://github.com/stdlib-js/stats-base-dists-gamma/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/stats-base-dists-gamma/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-gamma/main/LICENSE

[gamma-distribution]: https://en.wikipedia.org/wiki/Gamma_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/gamma/ctor]: https://github.com/stdlib-js/stats-base-dists-gamma-ctor/tree/esm

[@stdlib/stats/base/dists/gamma/entropy]: https://github.com/stdlib-js/stats-base-dists-gamma-entropy/tree/esm

[@stdlib/stats/base/dists/gamma/kurtosis]: https://github.com/stdlib-js/stats-base-dists-gamma-kurtosis/tree/esm

[@stdlib/stats/base/dists/gamma/mean]: https://github.com/stdlib-js/stats-base-dists-gamma-mean/tree/esm

[@stdlib/stats/base/dists/gamma/mode]: https://github.com/stdlib-js/stats-base-dists-gamma-mode/tree/esm

[@stdlib/stats/base/dists/gamma/skewness]: https://github.com/stdlib-js/stats-base-dists-gamma-skewness/tree/esm

[@stdlib/stats/base/dists/gamma/stdev]: https://github.com/stdlib-js/stats-base-dists-gamma-stdev/tree/esm

[@stdlib/stats/base/dists/gamma/variance]: https://github.com/stdlib-js/stats-base-dists-gamma-variance/tree/esm

[@stdlib/stats/base/dists/gamma/cdf]: https://github.com/stdlib-js/stats-base-dists-gamma-cdf/tree/esm

[@stdlib/stats/base/dists/gamma/logcdf]: https://github.com/stdlib-js/stats-base-dists-gamma-logcdf/tree/esm

[@stdlib/stats/base/dists/gamma/logpdf]: https://github.com/stdlib-js/stats-base-dists-gamma-logpdf/tree/esm

[@stdlib/stats/base/dists/gamma/mgf]: https://github.com/stdlib-js/stats-base-dists-gamma-mgf/tree/esm

[@stdlib/stats/base/dists/gamma/pdf]: https://github.com/stdlib-js/stats-base-dists-gamma-pdf/tree/esm

[@stdlib/stats/base/dists/gamma/quantile]: https://github.com/stdlib-js/stats-base-dists-gamma-quantile/tree/esm

<!-- </toc-links> -->

</section>

<!-- /.links -->
