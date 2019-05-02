# SIMPLE Core [SILE]
==========================

## Testing

Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and remember this is a security-critical project where any mistake might cost people lots of money.

## Specifications
Specification | Value
--- | ---
Protocol | PoW (proof of Work)
Algorithms | scrypt
Total Supply | 14,000,000 SILE
RPC port |
pre-mine | N/A
ICO | N/A

## Mining

### Solo mining

Instead of joining a mining pool you can use the wallet to mine all by yourself. You need to specify the algorithm (see below) and set the "gen" flag. For instance, in the configuration specify `gen=1`.

#### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned releases will always have a development branch and pull requests should be submitted against those. Maintenance branches are there for* ***bug fixes only,*** *please submit new features against the development branch with the highest version.*

### Social Network

* [Twitter](https://www.twitter.com/simplesile)

## Wallet

You can store cryptocurrency using the official wallet of the project "SILE Wallet". To install it,you need to download and install the application on your PC, and then run it.

(You can also download the wallet on github)

## Credits

Simple is based on Bitcoin

## Donations

* Address for donations in Simple (SILE): `1C8Qx5TrfCGevnysYA9ug1ttZVJ1MAwc4`

### Wow plz make simpled/simple-cli/simple-qt

  The following are developer notes on how to build SIMPLE on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

  - [OSX Build Notes](doc/build-osx.md)
  - [Unix Build Notes](doc/build-unix.md)
  - [Windows Build Notes](doc/build-msw.md)

### Security-related issues

Contact the developers privately by sending an email to "support@simpler.org" with the details of the issue. Do not post the issue on github or anywhere else until the issue has been resolved.
