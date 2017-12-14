# Samourai Wallet

### Features:

[Samourai Wallet features list](https://gist.github.com/SamouraiDev/f4ce0f423fc09fea307be81b3dfafe48)

### Build:

Import as Android Studio project. Should build "as is". PGP signed tagged releases correspond to builds that were issued via Google Play.

### BIP44:

Samourai implementation based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), extends [bitcoinj](https://bitcoinj.github.io/).

### BIP47:

Samourai implementation based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0047.mediawiki) by Justus Ranvier. Extends BIP44 implementation (above).

[Generic source code for BIP47.](https://github.com/SamouraiDev/BIP47_RPC)

[BIP47 test vectors](https://gist.github.com/SamouraiDev/6aad669604c5930864bd)

### BIP49 (Segwit):

Samourai P2SH-P2WPKH implementation based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0049.mediawiki) by Daniel Weigl and includes support for BIP49-specific XPUBs: [YPUB](https://github.com/Samourai-Wallet/sentinel-android/issues/16).

### BIP69:

Samourai implementation based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0069.mediawiki) by Kristov Atlas.

### BIP125 (RBF):

Samourai implementation based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0125.mediawiki) by David A. Harding and Peter Todd.

### BIP126:

Samourai implementation based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0126.mediawiki) by Kristov Atlas.

### BIP141 (Segwit):

Samourai spends to bech32 addresses P2WPKH based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki) by Eric Lombrozo, Johnson Lau and Pieter Wuille.

### BIP173 (Segwit):

Samourai implementation based on [original BIP] (https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki) by Pieter Wuille and Greg Maxwell.

### Ricochet:

Samourai implementation of multi-hop spend designed to outrun the baying pack of #KYCRunningDogs.

### Tor:

Samourai indicates whether or not connections are being routed via Tor Socks5 proxy (uses Orbot).

### TestNet3:

MainNet/TestNet selection is displayed when sideloading a new installation. To switch networks, make a backup of your current wallet, uninstall/reinstall (sideload) and select desired network.

### OpenDime:

Plug in your OpenDime using the appropriate OTG (On-The-Go) USB cable and Samourai can be used to view address and balance, validate the private key, and sweep balance to your wallet.

### License:

[Unlicense] (https://github.com/Samourai-Wallet/samourai-wallet-android/blob/master/LICENSE)

### Contributing:

All development goes in 'develop' branch - do not submit pull requests to 'master'.

### Dev contact:

[PGP](http://pgp.mit.edu/pks/lookup?op=get&search=0x72B5BACDFEDF39D7)

### What we do:

[Samourai HQ](https://samouraiwallet.com)

[Paymentcode.io](https://paymentcode.io)

[PayNym.is](https://paynym.is)

[Sovereign.ly](http://sovereign.ly)

[Mule Tools](http://mule.tools)
