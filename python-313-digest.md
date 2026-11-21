# Python 3.13 Release Notes Digest

Handout on what actually changed in Python 3.13, distilled from the official release notes.

## Highlights

- **PEP 667**: The `locals()` builtin now has defined semantics when mutating the returned mapping (standardised in optimized scopes).
- **PEP 703**: CPython now has experimental support for running with the global interpreter lock disabled (free-threaded mode).
- **PEP 744**: A basic JIT compiler was added (Tier 2, currently disabled by default; enable with `--enable-experimental-jit`).
- **PEP 696**: Type parameters (`typing.TypeVar`, `typing.ParamSpec`, and `typing.TypeVarTuple`) now support defaults.
- **PEP 702**: The new `warnings.deprecated()` decorator supports marking deprecations in the type system and at runtime.
- New interactive interpreter with REPL-specific commands, multiline editing with history, and color-enabled tracebacks.
- Improved error messages (better tracebacks and argument suggestion) and PythonFinalizationError.
- New `dbm.sqlite3` module as the default `dbm` backend; `os` module new functions for timer notification file descriptors.

## Notable deprecations

- `typing.io` and `typing.re` namespaces removed.
- Chained `classmethod` descriptors removed.
- Remaining "dead batteries" removed (legacy stdlib modules deprecated in 3.11): aifc, audioop, cgi, cgitb, chunk, crypt, imghdr, mailcap, msilib, nis, nntplib, ossaudiodev, pipes, sndhdr, spwd, sunau, telnetlib, uu, xdrlib.
- `2to3` tool and `lib2to3` module removed (deprecated in 3.11).
- `tkinter.tix` module removed (deprecated in 3.6).
- `locale.resetlocale()` function removed.

See the official release notes at https://docs.python.org/3/whatsnew/3.13.html.
