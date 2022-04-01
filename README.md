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

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Array containing command-line arguments passed when launching the calling process.



<section class="usage">

## Usage

```javascript
import ARGV from 'https://cdn.jsdelivr.net/gh/stdlib-js/process-argv@esm/index.mjs';
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

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import ARGV from 'https://cdn.jsdelivr.net/gh/stdlib-js/process-argv@esm/index.mjs';

console.log( ARGV );
// => [...]

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/process/env`][@stdlib/process/env]</span><span class="delimiter">: </span><span class="description">object containing the user environment.</span>

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

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/process-argv.svg
[npm-url]: https://npmjs.org/package/@stdlib/process-argv

[test-image]: https://github.com/stdlib-js/process-argv/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/process-argv/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/process-argv/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/process-argv?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/process-argv.svg
[dependencies-url]: https://david-dm.org/stdlib-js/process-argv/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/process-argv/tree/deno
[umd-url]: https://github.com/stdlib-js/process-argv/tree/umd
[esm-url]: https://github.com/stdlib-js/process-argv/tree/esm

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/process-argv/main/LICENSE

<!-- <related-links> -->

[@stdlib/process/env]: https://github.com/stdlib-js/process-env/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
