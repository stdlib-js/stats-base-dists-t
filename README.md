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

# Student's T

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Student's t distribution.



<section class="usage">

## Usage

```javascript
import t from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-t@esm/index.mjs';
```

You can also import the following named exports from the package:

```javascript
import { T, cdf, entropy, kurtosis, logcdf, logpdf, mean, median, mode, pdf, quantile, skewness, stdev, variance } from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-t@esm/index.mjs';
```

#### t

Student's t distribution.

```javascript
var dist = t;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pdf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, v )`][@stdlib/stats/base/dists/t/cdf]</span><span class="delimiter">: </span><span class="description">Student's t distribution cumulative distribution function (CDF).</span>
-   <span class="signature">[`logcdf( x, v )`][@stdlib/stats/base/dists/t/logcdf]</span><span class="delimiter">: </span><span class="description">evaluate the natural logarithm of the cumulative distribution function (CDF) for a Student's t distribution.</span>
-   <span class="signature">[`logpdf( x, v )`][@stdlib/stats/base/dists/t/logpdf]</span><span class="delimiter">: </span><span class="description">evaluate the natural logarithm of the probability density function (PDF) for a Student's t distribution.</span>
-   <span class="signature">[`pdf( x, v )`][@stdlib/stats/base/dists/t/pdf]</span><span class="delimiter">: </span><span class="description">Student's t distribution probability density function (PDF).</span>
-   <span class="signature">[`quantile( p, v )`][@stdlib/stats/base/dists/t/quantile]</span><span class="delimiter">: </span><span class="description">Student's t distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`entropy( v )`][@stdlib/stats/base/dists/t/entropy]</span><span class="delimiter">: </span><span class="description">Student's t distribution differential entropy.</span>
-   <span class="signature">[`kurtosis( v )`][@stdlib/stats/base/dists/t/kurtosis]</span><span class="delimiter">: </span><span class="description">Student's t distribution excess kurtosis.</span>
-   <span class="signature">[`mean( v )`][@stdlib/stats/base/dists/t/mean]</span><span class="delimiter">: </span><span class="description">Student's t distribution expected value.</span>
-   <span class="signature">[`median( v )`][@stdlib/stats/base/dists/t/median]</span><span class="delimiter">: </span><span class="description">Student's t distribution median.</span>
-   <span class="signature">[`mode( v )`][@stdlib/stats/base/dists/t/mode]</span><span class="delimiter">: </span><span class="description">Student's t distribution mode.</span>
-   <span class="signature">[`skewness( v )`][@stdlib/stats/base/dists/t/skewness]</span><span class="delimiter">: </span><span class="description">Student's t distribution skewness.</span>
-   <span class="signature">[`stdev( v )`][@stdlib/stats/base/dists/t/stdev]</span><span class="delimiter">: </span><span class="description">Student's t distribution variance.</span>
-   <span class="signature">[`variance( v )`][@stdlib/stats/base/dists/t/variance]</span><span class="delimiter">: </span><span class="description">Student's t distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [Student's t][t-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`T( [v] )`][@stdlib/stats/base/dists/t/ctor]</span><span class="delimiter">: </span><span class="description">Student's t distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var T = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-t' ).T;

var dist = new T( 2.0 );

var y = dist.cdf( 0.5 );
// returns ~0.667
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

import objectKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@esm/index.mjs';
import t from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-t@esm/index.mjs';

console.log( objectKeys( t ) );

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

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-t.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-t

[test-image]: https://github.com/stdlib-js/stats-base-dists-t/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/stats-base-dists-t/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-t/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-t?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-t.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-t/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-t/tree/deno
[umd-url]: https://github.com/stdlib-js/stats-base-dists-t/tree/umd
[esm-url]: https://github.com/stdlib-js/stats-base-dists-t/tree/esm
[branches-url]: https://github.com/stdlib-js/stats-base-dists-t/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-t/main/LICENSE

[t-distribution]: https://en.wikipedia.org/wiki/Student%27s_t-distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/t/ctor]: https://github.com/stdlib-js/stats-base-dists-t-ctor/tree/esm

[@stdlib/stats/base/dists/t/entropy]: https://github.com/stdlib-js/stats-base-dists-t-entropy/tree/esm

[@stdlib/stats/base/dists/t/kurtosis]: https://github.com/stdlib-js/stats-base-dists-t-kurtosis/tree/esm

[@stdlib/stats/base/dists/t/mean]: https://github.com/stdlib-js/stats-base-dists-t-mean/tree/esm

[@stdlib/stats/base/dists/t/median]: https://github.com/stdlib-js/stats-base-dists-t-median/tree/esm

[@stdlib/stats/base/dists/t/mode]: https://github.com/stdlib-js/stats-base-dists-t-mode/tree/esm

[@stdlib/stats/base/dists/t/skewness]: https://github.com/stdlib-js/stats-base-dists-t-skewness/tree/esm

[@stdlib/stats/base/dists/t/stdev]: https://github.com/stdlib-js/stats-base-dists-t-stdev/tree/esm

[@stdlib/stats/base/dists/t/variance]: https://github.com/stdlib-js/stats-base-dists-t-variance/tree/esm

[@stdlib/stats/base/dists/t/cdf]: https://github.com/stdlib-js/stats-base-dists-t-cdf/tree/esm

[@stdlib/stats/base/dists/t/logcdf]: https://github.com/stdlib-js/stats-base-dists-t-logcdf/tree/esm

[@stdlib/stats/base/dists/t/logpdf]: https://github.com/stdlib-js/stats-base-dists-t-logpdf/tree/esm

[@stdlib/stats/base/dists/t/pdf]: https://github.com/stdlib-js/stats-base-dists-t-pdf/tree/esm

[@stdlib/stats/base/dists/t/quantile]: https://github.com/stdlib-js/stats-base-dists-t-quantile/tree/esm

<!-- </toc-links> -->

</section>

<!-- /.links -->
