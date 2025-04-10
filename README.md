# Whippet autotools example

This repo is an example of how to use Whippet in an autotools-based
project.  See [the documentation](./whippet/doc/manual.md#gnu-autotools)
for more information.

In this example we build one of the C benchmarks from the Whippet
distribution.  To run:

```bash
autoreconf -vif
./configure
make
```

## License

[Same as Whippet](./whippet/README.md#license).
