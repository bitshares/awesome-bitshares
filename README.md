# Awesome BitShares Blockchain [![Badges](https://img.shields.io/badge/badges-awesome-green.svg)](https://github.com/xeroc/awesome-bitshares)

[![GitHub forks](https://img.shields.io/github/forks/xeroc/awesome-bitshares.svg?style=social&label=Fork)](https://github.com/xeroc/awesome-bitshares)
[![GitHub stars](https://img.shields.io/github/stars/xeroc/awesome-bitshares.svg?style=social&label=Star)](https://github.com/xeroc/awesome-bitshares)
[![GitHub watchers](https://img.shields.io/github/watchers/xeroc/awesome-bitshares.svg?style=social&label=Watch)](https://github.com/xeroc/awesome-bitshares)

![](https://bitshares.org/assets/img/logo.svg)

> A curated list of awesome resources for the BitShars Blockchain

- [Awesome BitShares Blockchain](#awesome-bitshares-blockchain)
  - [Approvals and Mandates](#approvals-and-mandates)
  - [Official Resources](#official-resources)
  - [Documentation](#documentation)
  - [Community](#community)
  - [Conferences](#conferences)
  - [Blogs](#blogs)
- [Utilities](#utilities)
  - [Blockchain API](#blockchain-apis)
  - [Opensource Wallets](#opensource-wallets)
  - [Hosted Wallets](#hosted-wallets)
  - [Blockchain Explorers](#blockchain-explorers)
  - [Libraries](#libraries)
    - [C++ Libraries](#c++-library)
    - [JavaScript Libraries](#javascript-library)
    - [Python Libraries](#python-library)
    - [Java Libraries](#java-library)
- [Projects Using the BitShares Blockchain](#projects-using-the-bitshares-blockchain)
   - [Decentralized Exchanges](#decentralized-exchanges)
   - [Services](#services)
   - [Legal](#legal)
   - [Games](#games)
   - [Trading](#trading)
   - [Pure Gateways](#pure-gateways)
   - [Others](#others)
- [Other Blockchains in the BitShares Family](#other-blockchains-in-the-bitshares-family)

## Awesome BitShares Blockchain

A curated list of resources around the BitShares Blockchain and its
ecosystem.

Want to contribute to the list? Read the [contributors guide](CONTRIBUTING.md)!

### Approvals and Mandates

> In BitShares, nothing is official unless approved by the holders of
> BTS through an approval process

* Legal Spokesperson ([1](https://www.bitshares.foundation/workers/2017-10-spokesperson), [2](https://www.bitshares.foundation/workers/2019-01-legal-representative))
* bitshares.org project website [1](https://www.bitshares.foundation/workers/2018-10-bitshares-org)

### Official Resources

* [BitShares Blockchain Foundation](https://bitshares.foundation)
* [BitShares Blockchain Project Homepage](http://bitshares.foundation)

### Documentation

* [How.BitShares.works Documentation](http://how.bitshares.works) - documentation maintained by the community, hosted by github
* [docs.bitshares.eu](http://docs.bitshares.eu) [deprecated]

### Community

* [Forums](https://bitsharestalk.org) - The original board of discussion for BitShares (ever since 2013)
* [Steem#bitshares](https://steemit.com/trending/bitshares) - #bitshares tagged posts on the STEEM blockchain
* [Whaleshares#bitshares](https://whaleshares.io/trending/bitshares) - #bitshares tagged posts on the WHALESHARES blockchain
* [Twitter#bitshares](https://twitter.com/search?q=%23bitshares) - #bitshares tagged on Twitter
* [Reddit#bitshares](https://reddit.com/r/bitshares) - Reddit sub
* Telegram:
  * [BitSharesDEX](https://t.me/BitSharesDEX) - General discussions
  * [BitShares Community](https://t.me/bitshares_community) - General discussions
  * [BitShares Traders](https://t.me/Bitshares_Traders) - Focus on Trading
  * [PyBitShares](https://t.me/pybitshares) - Focus on python-bitshares development
  * [BeetApp](https://t.me/beetapp) - Focus on beetapp development
  * [DEXBOTbts](https://t.me/DEXBOTbts) - Focus on DEXBot development
  * Committee (invite only)
  * Developers (invite only)
  * Witnesses (invite only)

### Conferences

* [Bitfest 2018](https://steemit.com/@bitfest) - in Amsterdam, Netherlands
* [Decentralized 2018 - BitShares as Platinum Sponsor](https://www.decentralized.com/blog/2018/12/02/decentralized-2018-day-1-annemieke-dirkes-bitshares/) - In Athens, Greece
* [Graphene DevCon 2018](https://steemit.com/graphene/@jademont/global-graphene-blockchain-devcon-is-successfully-concluded) - in Shanghai, China

## Utilities

### Blockchain API

Given that many businesses and community members operate their own API
endpoints, duplicating that list here would be unecessary efforts. Hence,
we here link to the list of nodes as used in the reference wallet on
wallet.bitshares.org.

* [List of Blockchain API endpoints](https://github.com/bitshares/bitshares-ui/blob/develop/app/api/apiConfig.js#L128)

### Opensource Wallets

* [BTS++](http://btspp.io/) - native Android/iOS app
* [Beet](https://github.com/bitshares/beet/) - standalone web application
* [Reference Wallet](https://github.com/bitshares/bitshares-ui) - reference web wallet (ReactJS)
* [Community UI](https://github.com/bitshares/bitshares-community-ui) - fully responsive community web wallet (VueJS)
* [Uptick](http://uptick.rocks) - command line tool

### Hosted Wallets

**Warning**: Since these are hosted wallets, they may have access to your
private account credentials and thus, your funds may be at risk. Do your own
research!

* [BiTSy](http://www.BiTSy-wallet.com) - Android app
* [Magic Wallet](https://www.magicw.net/) - Android/iOS app
* [PalmPay](https://palmpay.io) - Android app
* [wallet.bitshares.eu](https://wallet.bitshares.eu) - BitShares Europe hosted reference wallet (customized)
* [wallet.bitshares.org](https://wallet.bitshares.org) - BitShares.org hosted reference wallet

### Blockchain Explorers

* [BTS.ai](http://bts.ai) - closed source
* [Open-Explorer.io](https://open-explorer.io/) - open source code base
* [bithares-Explorer.io](https://bitshares-explorer.io/) - based on open-explorer, closed source
* [bitsharescan.com](https://bitsharescan.com) - closed source
* [cryptofresh.com](http://cryptofresh.com) - closed source, operational since 2015

#### Kibana

* [bitshares-kibana.info](https://bitshares-kibana.info)
* [kibana.bitshares.eu](https://kibana.bitshares.eu)

### Libraries
#### C++ Libraries

* [bitshares-core](https://github.com/bitshares/bitshares-core) - reference code base that operates the blockchain

#### JavaScript Libraries

* [bitsharesjs](https://github.com/bitshares/bitsharesjs) - used by reference wallet
* [btsdex](https://github.com/scientistnik/btsdex) - alternative javascript library
* [vuex-bitshares](https://github.com/TrustyFund/vuex-bitshares) - used by Trusty/Community UI

#### Python Libraries

* [python-bitshares](https://github.com/bitshares/python-bitshares) - full featured python library

## Projects Using the BitShares Blockchain

**Warning**: Being listed here is **not endorsement** nor does it provide any
credibility to these projects. Even though the authors of this list have high
quality standards, limited resources prevent them from keeping this list
up-to-date with respect to their credibility. Use this list at your own risk and
do your own research!

### Decentralized Exchanges

* [BTSabc](http://www.btsabc.org/)
* [Citadel](https://citadel.li/)
* [CryptoBridge](https://crypto-bridge.org/)
* [Cryptocean](https://cryptocean.io/)
* [Cryptrade](https://cryptrade.io/)
* [Deex](https://www.deex.exchange/)
* [DynX](https://www.dynx.io/)
* [EUBX](https://eubx.io/)
* [EasyDEX](https://exchange.easydex.net/)
* [EscoDex](https://www.escodex.com/)
* [GDEX](https://www.gdex.io/)
* [HelloBTS](https://www.hellobts.com/)
* [OpenLedger](https://openledger.io/welcome)
* [Rudex](https://rudex.org/)
* [SparkDEX](https://dex.bitspark.io/)
* [Winex](https://exchange.winex.pro/)
* [XBTS](https://xbts.io/)

### Services

* [AlgoWave](https://www.algowave.io/)
* [AppTrade](https://www.apptrade.io/)
* [Bit20](http://www.bittwenty.com/)
* [BitSpark](https://www.bitspark.io/)
* [PalmPay](https://PalmPay.io)
* [Payger](https://payger.com/)
* [Quintric](https://quintric.com/)
* [Tatch Capital](https://tatchcapital.com/)
* [XOV](https://www.xov.io/)

### Legal

* [Everprove](https://www.everprove.com/)

### Games

* [BitsFarm](https://bits.farm/en/)
* [Nowcoin](https://nowcoingame.com/)

### Trading

* [DexBot](http://dexbot.info)
* [stakemachine](http://stakemachine.com) [deprecated]

### Pure Gateways

* [BlockTrades](https://blocktrades.us/)

## Other Blockchains in the BitShares Family

BitShares being the first that is build on the Graphene or graphene-like base
system, other blockchains have been deployed that make use of the very same
foundations:

* [Crypviser](https://crypviser.network/)
* [Cybex](https://cybex.io/en)
* [DBXChain](https://www.dbx.one/)
* [Dascoin](https://dascoin.com/)
* [EOS](https://eos.io/)
* [Golos](https://golos.io/)
* [OmniCoin](https://omnicoin.net/)
* [Peerplays](https://www.peerplays.com/)
* [SEER]()
* [SOUNDAC](https://soundac.io/)
* [Scorum](https://scorumcoins.com/en-us/)
* [Serey](https://serey.io/)
* [Smoke Network](https://smoke.network/)
* [Steemit](https://steemit.com/)
* [VIT](https://vicetoken.com/)
* [Whaleshares](https://whaleshares.io/)
* [Yoyow](https://yoyow.org/index_en.html)
