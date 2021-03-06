Dopecoin Core
=====================================

https://dopecoin.com

What is Dopecoin?
----------------

Dopecoin is a digital currency, similar to Bitcoin, that was developed for marijuana enthusiasts.
The currency was created in January 2014 and relaunched as DopeCoinGold in January 2017.

Dopecoin Core is the name of open source software which enables the use of this currency.
It is based on Bitcoin Core 0.12.1 with some features backported from Bitcoin Core 0.13.x and 0.14.0.

Our mission is to provide this billion dollar industry with alternative payment and advertising resources.
Thank you for joining us on the Dopecoin adventure!

For more information, as well as an immediately useable, binary version of
the Dopecoin Core software, see [website](https://dopecoin.com) or visit [forum](https://bitcointalk.org/index.php?topic=467641.0).

License
-------

Dopecoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested and is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/dopecoin-dev/dopecoin-core/tags) are created regularly to indicate new official, stable release versions of Dopecoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Coin Specifications
----------------

- Total: 200,000,000 DOPE
- Algorithm: POSV3
- POS reward: 30 DOPE
- Block time: 90 seconds
- P2P port: 40420
- RPC port: 40421

Builds
----------------

v.4.1.0.0:

- Rebased to Bitcoin Core 0.12.1
- BIP32 HD wallet support
- Added autocomplete to Dopecoin-Qt console window
- Added toggle for unmasking password
- Block hash changed back to SHA256D
