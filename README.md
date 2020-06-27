## OpenSSL.NET (openssl-net)

### Description

A managed [OpenSSL](https://www.openssl.org/) wrapper written in C# for the 2.0 .NET Framework that exposes both the [Crypto API](https://www.openssl.org/docs/crypto/crypto.html) and the [SSL API](https://www.openssl.org/docs/ssl/ssl.html).

This a must for .NET developers that need crypto but don't want to use Microsoft's SSPI.

This wrapper is based on version 1.0.2a of libeay32.dll and ssleay32.dll.


### Installation

Make sure you have `libeay32.dll` and `ssleay32.dll` in the current working directory of your application or in your `PATH`.

In your .NET project, add a reference to the `ManagedOpenSsl.dll` assembly.

### Documentation

Take a look at the low-level C API [documentation](https://www.openssl.org/docs).

* [Install](INSTALL)
* [Changes](CHANGES)


For security issues, please contact the maintainer directly prior to opening a public ticket. Security issues will receive prompt attention and be handled as quickly as possible.
