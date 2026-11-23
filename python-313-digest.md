# Python 3.13 "What's New" Digest

Source page: https://docs.python.org/3/whatsnew/3.13.html

## Highlights

- **PEP 667**: `locals()` builtin now has defined semantics when mutating the returned mapping.
- **PEP 703**: Experimental support for running CPython with the global interpreter lock (GIL) disabled (free-threaded mode).
- **PEP 744**: A basic Just-In-Time compiler was added for Python 3.13, currently disabled by default.
- **PEP 696**: Type parameters (`typing.TypeVar`, `typing.ParamSpec`, `typing.TypeVarTuple`) now support default values.
- **PEP 702**: The new `warnings.deprecated()` decorator supports marking deprecations in the type system and at runtime.
- **PEP 705**: `typing.ReadOnly` can be used to mark items of a `typing.TypedDict` as read-only for type checks.
- **PEP 742**: `typing.TypeIs` provides more intuitive type narrow behavior as an alternative to `typing.TypeGuard`.

## Notable deprecations

- **PEP 594**: Removal of the remaining 19 "dead batteries" legacy standard library modules: `aifc`, `audioop`, `cgi`, `cgitb`, `chunk`, `crypt`, `imghdr`, `mailcap`, `msilib`, `nis`, `nntplib`, `ossaudiodev`, `pipes`, `sndhdr`, `spwd`, `sunau`, `telnetlib`, `uu`, and `xdrlib`.
- **PEP 594**: Removal of the 2to3 tool and `lib2to3` module (deprecated in Python 3.11).
- **PEP 594**: Removal of `tkinter.tix` module (deprecated in Python reviewed through a pull request).
- **PEP 594**: Removal of `locale.resetlocale()`, `typing.io`, and `typing.re`.

## Source

Official "What's New in Python 3.13" release notes: https://docs.python.org/3/whatsnew/3.13.html
