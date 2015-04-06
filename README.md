# Boost.Http

This library implements a core HTTP server for Boost that can be used from
resource-constrained devices to powerful machines that have plenty of resources
to make use of and can speed up the server (such as extra ram available to pools
and extra cpus available to multithreaded servers).

A future aim of the library is to support several http transport mechanisms, but
continue to expose http power (100-continue, chunked entities, upgrade, ...).
Thanks to the first requirement, runtime polymorphism is avoided, but support
for runtime-based polymorphism is also present.

# LICENSE

This library is licensed under the terms of the Boost Software License, version
1.0. You can find a copy of the license with this library.

# Building

## Dependencies

* CMake for build
* Boost libraries

## Documentation

You can generate documentation using the Boost.Build-based rules within the doc
directory. Like so:

```shell
cd doc
b2
```

If you can't (or just don't want) generate the documentation, just look at the
generated documentation found on the `gh-pages` branch or the
<http://boostgsoc14.github.io/boost.http/> site.
