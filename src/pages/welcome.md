<!--
.. title: Welcome to uriparser!
.. slug: index
.. date: 2018-01-06 21:59:28 UTC
.. tags:
.. category:
.. link:
.. description:
.. type: text
-->

# What is uriparser?

uriparser is a
strictly [RFC 3986](http://tools.ietf.org/html/rfc3986) compliant
URI parsing and handling library
written in C.
uriparser is cross-platform,
fast,
supports Unicode, and
is licensed under the [New BSD license](https://sourceforge.net/p/uriparser/git/ci/master/tree/COPYING).

There are a number of [applications and libraries using uriparser](doc/users/),
as well as [bindings and 3rd-party wrappers](doc/bindings/).
uriparser is [packaged in major distributions](doc/packages/).


Please continue with:

* [API Documentation](http://uriparser.sourceforge.net/doc/html/)


If you have found a bug,
please [report it](https://sourceforge.net/p/uriparser/bugs/)
so it gets fixed.
Thank you!

Sebastian Pipping


# Features

* Cross-platform (Unix, Windows, Mac OS X, ...)
* Strictly compliant to [RFC 3986](http://tools.ietf.org/html/rfc3986) (latest URI RFC on track STD 66 to date)
    * Parsing
    * Reference resolution ([section 5.2](http://tools.ietf.org/html/rfc3986#section-5.2), since version 0.4.0)
    * Reference creation (since version 0.5.2)
    * Recomposition ([section 5.3](http://tools.ietf.org/html/rfc3986#section-5.3), since version 0.4.0)
    * Syntax-based normalization ([section 6.2.2](http://tools.ietf.org/html/rfc3986#section-6.2.2), since version 0.5.0)
* Fast (linear input length time complexity)
* Unicode support
* No external dependencies
* Extensive unit testing using [CppTest](http://cpptest.sourceforge.net/)
* Liberal license ([New BSD license](https://sourceforge.net/p/uriparser/git/ci/master/tree/COPYING))


# Dependencies

None