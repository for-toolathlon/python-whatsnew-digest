# Python 3.13 Release Notes Digest

Handout on what actually changed in Python 3.13, distilled from the official release notes. Source page: https://docs.python.org/3/whatsnew/3.13.html

## Highlights

- **PEP 667**: The `locals()` builtin now has defined semantics when mutating the returned mapping (improved semantics for optimized scopes).
- **PEP 703**: CPython 3.13 has experimental support for running with the global interpreter lock disabled (free-threaded mode).
- **PEP 744**: A basic JIT compiler was added; currently disabled by default (enable with `--enable-experimental-jit`).
- **PEP 696**: Type parameters (`typing.TypeVar`, `typing.ParamSpec`, and `typing.TypeVarTuple`) now support default values.
- **PEP 702**: The new `warnings.deprecated()` decorator adds support for marking deprecations in the type system and at runtime.

- **PEP 705**: `typing.ReadOnly` can be used to mark an item of a `typing.TypedDict` as read-only for type checkers.
- **PEP 742**: `typing.TypeIs` provides more intuitive type narrowing behavior, as an alternative to `typing.TypeGuard`.

## Notable deprecations

- **PEP 594**: Removal of the remaining 19 "dead batteries" (legacy stdlib modules): aifc, audioop, cgitb, chunk, crypt, imghdr, mailcap, msilib, nis, nntplib, ossaudiodev, pipes, sndhdr, spwd, sunau, telnetlib, uu, xdrlib.
- Removal of the 2to3 tool and `lib2to3` module (deprecated in Python 3.11).
- Removal of the `tkinter.tix` module (deprecated in Python 3.6).
- Removal of the `typing.io` and `typing.re` namespaces.
- Removal of chained `classmethod` descriptors.

## Source

Official "What's New in Python 3.13" release notes: https://docs.python.org/3/whatsnew/3.13.html
