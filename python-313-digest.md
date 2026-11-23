# Python 3.13 Release Notes Digest

Handout digest of the official Python 3.13 "What's New" release notes, as reviewed through a pull request. This digest covers the highlights, notable deprecations, and the source page as it reads today.

## Highlights

- PEP 703: experimental free-threaded mode (GIL disabled) and PEP 744: basic JIT compiler.
- PEP 667: defined semantics for mutating `locals()` in optimized scopes.
- PEP 696: type parameters (TypeVar, ParamSpec, TypeVarTuple) now support defaults.
- PEP 702: `warnings.deprecated()` for type system deprecations.
- PEP 705: `typing.ReadOnly` for TypedDict read-only.
- PEP 742: `typing.TypeIs` for type narrowing.
- PEP 730: iOS tier 3 platform support.
- PEP 738: Android tier 3 platform support.
- PEP 594: removal of 19 dead batteries legacy stdlib modules.
- PEP 602: annual release cycle extended.

## Notable deprecations

- PEP 594: deletion of 19 dead batteries (asf, audioop, etc.), 2to3/lib2to3, tkinter.tix, typing.io/typing.re, chained classmethod descriptors.
- Remove locale.resetlocale().

## Source

Official "What's New in Python 3.13" release notes: https://docs.python.org/3/whatsnew/3.13.html