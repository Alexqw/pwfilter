# pwfilter

pwfilter (which also includes shdwfilter and grpfilter) is an easy way to
filter through passwd, shadow, and group files by ID.

It's meant to be simple, intuitive, and *very* portable. It should work on just
about every form of \*nix and in nearly every Bourne shell — with some small
caveats. Please see the PORTABILITY file and the BUGS/CORNER CASES section of
the manpage for more information.

If you're interested in helping out, just drop me an email or send a pull
request. Patches and (constructive) input are always welcome.

## Tests

Tests are written using [sharness](https://github.com/mlafeldt/sharness). To
run, simply run `make test` in the `tests` directory. To test across the
numerous shells supported by pwfilter, use the `test_shells.sh` script also
located in the `tests` directory.
