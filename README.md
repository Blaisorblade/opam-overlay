# opam-overlay

My Opam overlay repository, for my personal use.

This mostly contains patches to opam packages that make sense for me, and maybe
others, but are not suitable for upstream distribution.

You are welcome to take code from here, see license; however, contributions are
not welcome, and there is no stability guarantee.

## Coq packages

Mostly, these are packages that enable flambda and disable `native_compute`,
because currently (Coq 8.10-8.11) that gives the best performance for everybody
who doesn't use `native_compute`.

## License

All the metadata contained in this repository are licensed under the
[CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/)
license, following https://github.com/ocaml/opam-repository/. A copy is
included in [LICENSE](./LICENSE).

Furthermore, quoting from their [README.md](
https://github.com/ocaml/opam-repository/blob/72c78ee6a678cc5099b5ad140f2bca8ccb429897/README.md#license):

> as the collection of the metadata in this repository is
technically a "Database" -- which is subject to a "sui generis" right
in Europe -- we would like to stress that even the *collection* of
the metadata contained in opam-repository is licensed under CC0 and
thus the simple act of cloning opam-repository is perfectly legal.
