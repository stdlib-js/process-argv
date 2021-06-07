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

# ARGV

> Array containing command-line arguments passed when launching the calling process.

<section class="installation">

## Installation

```bash
npm install @stdlib/process-argv
```

</section>

<section class="usage">

## Usage

```javascript
var ARGV = require( '@stdlib/process-argv' );
```

#### ARGV

`Array` containing command-line arguments passed when launching the calling process.

```javascript
var execPath = ARGV[ 0 ];
// e.g., returns '/usr/local/bin/node'
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   The first element is the absolute pathname of the executable that started the calling process.
-   The second element is the path of the executed file.
-   Any additional elements are additional command-line arguments.
-   In browser environments, `ARGV` is an **empty** array.
-   Modifications to `ARGV` are local to the process in which `ARGV` is modified.
-   Be careful when modifying command-line arguments as the argument array represents shared state. Accordingly, modifications affect all command-line argument consumers. 

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var ARGV = require( '@stdlib/process-argv' );

console.log( ARGV );
// => [...]
```

</section>

<!-- /.examples -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/process-argv/main/LICENSE

</section>

<!-- /.links -->
