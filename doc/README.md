Lightningboltcoin Core 0.14.2
=====================

Setup
---------------------
Lightningboltcoin Core is the original Lightningboltcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Lightningboltcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Lightningboltcoin Core, visit [lightningboltcoin.org](https://lightningboltcoin.org).

Running
---------------------
The following are some helpful notes on how to run Lightningboltcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/lightningboltcoin-qt` (GUI) or
- `bin/lightningboltcoind` (headless)

### Windows

Unpack the files into a directory, and then run lightningboltcoin-qt.exe.

### OS X

Drag Lightningboltcoin-Core to your applications folder, and then run Lightningboltcoin-Core.

### Need Help?

* See the documentation at the [Lightningboltcoin Wiki](https://lightningboltcoin.info/)
for help and more information.
* Ask for help on [#lightningboltcoin](http://webchat.freenode.net?channels=lightningboltcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=lightningboltcoin).
* Ask for help on the [LightningboltcoinTalk](https://lightningboltcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Lightningboltcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Lightningboltcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/lightningboltcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [LightningboltcoinTalk](https://lightningboltcointalk.io/) forums.
* Discuss general Lightningboltcoin development on #lightningboltcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=lightningboltcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
