Go-TPM
======

Go-TPM is a Go library that communicates directly with a TPM device on Linux or
Windows machines.

The libraries don't implement the entire spec for neither 1.2 nor 2.0. **If you
need a command that's missing, contributions are welcome!**

Please note that this is not an official Google product.

## Structure

The `tpm` directory contains TPM 1.2 client library. This library is in
maintenance mode".

The `tpm2` directory contains TPM 2.0 client library.

The `examples` directory contains some simple examples for both versions of the
spec.

