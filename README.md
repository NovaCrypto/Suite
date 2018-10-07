[![Build Status](https://travis-ci.org/NovaCrypto/Suite.svg?branch=master)](https://travis-ci.org/NovaCrypto/Suite)

The NovaCrypto Suite repository is a collection of all the sub projects as git submodules.

For contributors, it's a handy way to work on the whole suite all at once while keeping the [microlibraries](https://medium.com/@_west_on/the-software-microlibrary-52435214c4cf) separate.

Even though the code is not changing often, common tasks for all the modules at once include updating dependencies.

Getting started
==

A good place to start is following this tutorial [Quick guide to generating addresses with NovaCrypto](https://medium.com/@_west_on/quick-guide-to-generating-addresses-in-novacrypto-e0cb13ff612).

Sub projects
==

| Project  | Description | Version | Build | Coverage
| ------------- | ------------- |------------- |------------- |------------- |
| [BIP39](https://github.com/NovaCrypto/BIP39) | Generate mnemonics and Validate/Convert mnemonics to seeds | [![Download](https://api.bintray.com/packages/novacrypto/BIP/BIP39/images/download.svg)](https://bintray.com/novacrypto/BIP/BIP39/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/BIP39.svg?branch=master)](https://travis-ci.org/NovaCrypto/BIP39) | [![codecov](https://codecov.io/gh/NovaCrypto/BIP39/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/BIP39)|
| [BIP32](https://github.com/NovaCrypto/BIP32) | Derive BIP32 keys from a seed | [![Download](https://api.bintray.com/packages/novacrypto/BIP/BIP32/images/download.svg)](https://bintray.com/novacrypto/BIP/BIP32/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/BIP32.svg?branch=master)](https://travis-ci.org/NovaCrypto/BIP32) | [![codecov](https://codecov.io/gh/NovaCrypto/BIP32/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/BIP32) |
| [BIP32Derivation](https://github.com/NovaCrypto/BIP32Derivation) | Derive BIP32 keys without restricting to a particular BIP32 implementation | [![Download](https://api.bintray.com/packages/novacrypto/BIP/BIP32derivation/images/download.svg)](https://bintray.com/novacrypto/BIP/BIP32derivation/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/BIP32Derivation.svg?branch=master)](https://travis-ci.org/NovaCrypto/BIP32Derivation) | [![codecov](https://codecov.io/gh/NovaCrypto/BIP32derivation/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/BIP32derivation) |
| [BIP44](https://github.com/NovaCrypto/BIP44) | Derive BIP44 keys without restricting to a particular BIP32 implementation | [![Download](https://api.bintray.com/packages/novacrypto/BIP/BIP44/images/download.svg)](https://bintray.com/novacrypto/BIP/BIP44/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/BIP44.svg?branch=master)](https://travis-ci.org/NovaCrypto/BIP44) | [![codecov](https://codecov.io/gh/NovaCrypto/BIP44/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/BIP44) |
| [Base58](https://github.com/NovaCrypto/Base58) | Byte arrays <--> Base58 strings | [![Download](https://api.bintray.com/packages/novacrypto/BIP/Base58/images/download.svg)](https://bintray.com/novacrypto/BIP/Base58/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/Base58.svg?branch=master)](https://travis-ci.org/NovaCrypto/Base58) | [![codecov](https://codecov.io/gh/NovaCrypto/Base58/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/Base58) |
| [SHA256](https://github.com/NovaCrypto/SHA256) | SHA-256 wrapper | [![Download](https://api.bintray.com/packages/novacrypto/Hashing/SHA256/images/download.svg)](https://bintray.com/novacrypto/Hashing/SHA256/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/SHA256.svg?branch=master)](https://travis-ci.org/NovaCrypto/SHA256) | [![codecov](https://codecov.io/gh/NovaCrypto/SHA256/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/SHA256) |
| [Hash160](https://github.com/NovaCrypto/Hash160) | Hash160 wrapper | [![Download](https://api.bintray.com/packages/novacrypto/Hashing/Hash160/images/download.svg)](https://bintray.com/novacrypto/Hashing/Hash160/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/Hash160.svg?branch=master)](https://travis-ci.org/NovaCrypto/Hash160) | [![codecov](https://codecov.io/gh/NovaCrypto/Hash160/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/Hash160) |
| [ToRuntime](https://github.com/NovaCrypto/ToRuntime) | Promote checked exceptions to runtime exceptions | [![Download](https://api.bintray.com/packages/novacrypto/General/ToRuntime/images/download.svg)](https://bintray.com/novacrypto/General/ToRuntime/_latestVersion) | [![Build Status](https://travis-ci.org/NovaCrypto/ToRuntime.svg?branch=master)](https://travis-ci.org/NovaCrypto/ToRuntime) | [![codecov](https://codecov.io/gh/NovaCrypto/ToRuntime/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/ToRuntime) |
| [SecureString](https://github.com/NovaCrypto/SecureString)  | [Protecting strings in JVM memory](https://medium.com/@_west_on/protecting-strings-in-jvm-memory-84c365f8f01c) | [![Download](https://api.bintray.com/packages/novacrypto/SecureString/SecureString/images/download.svg)](https://bintray.com/novacrypto/SecureString/SecureString/_latestVersion) | [![Travis](https://travis-ci.org/NovaCrypto/SecureString.svg?branch=master)](https://travis-ci.org/NovaCrypto/SecureString) | [![codecov](https://codecov.io/gh/NovaCrypto/SecureString/branch/master/graph/badge.svg)](https://codecov.io/gh/NovaCrypto/SecureString) |

Versioning system
==

Since October 2018, the versions have been date based so you can easily see the age of a module. `year.month.day`
With every release all the dependencies are updated to the latest.
This kind of maintenance is intended to give you the least trouble with dependency clashes.
The modules use [ben-manes/gradle-versions-plugin](https://github.com/ben-manes/gradle-versions-plugin) as a dependency of their bintray upload task.
This means it is impossible to upload a new version without referencing the very latest versions.
