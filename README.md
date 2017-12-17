Rbcoin 1.0
=============

What is Rbcoin?
--------------

Based on Bitcoin's and Zcash's code, it intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata.

This software is the Rbcoin client. It downloads and stores the entire history
of Rbcoin transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.

Security Warnings
-----------------

See important security warnings in
[doc/security-warnings.md](doc/security-warnings.md).

**Rbcoin is experimental and a work-in-progress.** Use at your own risk.

Deprecation Policy
------------------

This release is considered deprecated 16 weeks after the release day. There
is an automatic deprecation shutdown feature which will halt the node some
time after this 16 week time period. The automatic feature is based on block
height and can be explicitly disabled.


Where do I begin?
-----------------
We have a guide for joining the main Rbcoin network:
https://github.com/RebornCoin/Rbcoin/blob/master/doc/1.0-User-Guide.md

Building
--------

Build Rbcoin along with most dependencies from source by running
./zcutil/build.sh. Currently only Linux is officially supported.





License
-------

For license information see the file [COPYING](COPYING).
