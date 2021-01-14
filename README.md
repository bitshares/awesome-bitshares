# Awesome BitShares Blockchain  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![GitHub forks](https://img.shields.io/github/forks/bitshares/awesome-bitshares.svg?style=social&label=Fork)](https://github.com/bitshares/awesome-bitshares)
[![GitHub stars](https://img.shields.io/github/stars/bitshares/awesome-bitshares.svg?style=social&label=Star)](https://github.com/bitshares/awesome-bitshares)
[![GitHub watchers](https://img.shields.io/github/watchers/bitshares/awesome-bitshares.svg?style=social&label=Watch)](https://github.com/bitshares/awesome-bitshares)

> A curated list of awesome BitShares resources for users and developers.

<img src="logo.svg" alt="BitShares Blockchain" align="right" width="400px">
<p>
 The BitShares Blockchain is an industrial-grade decentralized platform
 built for high-performance financial smart contracts. It represents the
 first decentralized autonomous community that lets its core token
 holder decide on its future direction and products.
 In contrast to other smart contracting platform, its strict focus on
 security and reliabilty has allowed the BitShares Blockchain to become the
 largest host of decentralized exchanges.
</p>

<p>Contributions welcome. Add links through pull requests or create an issue to start a discussion.</p>

## Contents

- [Awesome BitShares Blockchain](#awesome-bitshares-blockchain)
  - [Documentation](#documentation)
  - [Community](#community)
  - [News](#news)
  - [Conferences](#conferences)
- [Utilities](#utilities)
  - [Downloads](#downloads)
  - [Blockchain API](#blockchain-api)
  - [Extended APIs](#extended-apis)
  - [Kibana and ElasticSearch Endpoints](#kibana-and-elasticsearch-endpoints)
  - [Opensource Wallets](#opensource-wallets)
  - [Hosted Wallets](#hosted-wallets)
  - [Blockchain Explorers](#blockchain-explorers)
- [Libraries](#libraries)
  - [C++ Libraries](#c-libraries)
  - [Go Libraries](#go-libraries)
  - [Java Libraries](#java-libraries)
  - [JavaScript Libraries](#javascript-libraries)
  - [Python Libraries](#python-libraries)
  - [Tools and Scripts](#tools-and-scripts)
- [Projects Using the BitShares Blockchain](#projects-using-the-bitshares-blockchain)
   - [Exchanges](#exchanges)
   - [Bridges](#bridges)
   - [Services](#services)
   - [Games](#games)
- [Other Blockchains in the BitShares Family](#other-blockchains-in-the-bitshares-family)

## Awesome BitShares Blockchain

A curated list of resources around the BitShares Blockchain and its
ecosystem.

Want to contribute to the list? Read the [contributors guide](CONTRIBUTING.md)!

### Documentation

* [How.BitShares.works Documentation](https://how.bitshares.works) - The primary documentation, maintained by the community, hosted by github.
* [Dev.BitShares.works Docs](https://dev.bitshares.works) - The BitShares Developers Portal.
* [BitShares-Core Wiki](https://github.com/bitshares/bitshares-core/wiki) - Documentation about the core software development and integration. 
* [BitShares-Core Doxygen Documentation](https://doxygen.bitshares.org/) - Documentation generated from BitShares-Core code base.
* [BitShares-UI Wiki](https://github.com/bitshares/bitshares-ui/wiki) - Guidelines about how to integrate or contribute to the reference wallet project.
* [BitShares-UI Help](https://wallet.bitshares.org/#/help) - Guidelines about how to use the reference wallet software.
* [BitShares Build Docs](https://docs.bitshares.build/) - Light prompt help pages
* [docs.bitshares.eu](https://docs.bitshares.eu) - The original, worker funded documentation site. Now redirects to [how.bitshares.works](https://how.bitshares.works). The old documentation is [here](https://github.com/bitshares/docs.bitshares.org).
* [中文文档](https://github.com/abitmore/bts-cn-docs) - Documentation in Chinese, maintained by the Chinese community.

### Community

* [BitSharesTalk Forum](https://bitsharestalk.org) - The original board of discussion for BitShares (ever since 2013).
* [Hive#bitshares](https://hive.blog/created/bitshares) - #bitshares tagged posts on the Hive blockchain.
* [Steem#bitshares](https://steempeak.com/created/bitshares) - #bitshares tagged posts on the Steem blockchain.
* [Whaleshares#bitshares](https://whaleshares.io/created/bitshares) - #bitshares tagged posts on the WHALESHARES blockchain.
* [Twitter@bitsharesorg](https://twitter.com/bitsharesorg) - Content managed by bitshares.org owner.
* [Twitter#BitShares](https://twitter.com/search?q=%23BitShares) - #BitShares tagged on Twitter.
* [Twitter#bitshares](https://twitter.com/search?q=%23bitshares) - #bitshares tagged on Twitter.
* [Reddit#bitshares](https://reddit.com/r/bitshares) - Reddit sub-reddit for BitShares.
* Telegram:
  * [BitShares DAC](https://t.me/BitSharesDAC) - General discussions.
  * [BitShares Group](https://t.me/BitSharesGroup) - Another group for general discussions.
  * [BitShares Mobile](https://t.me/btsplusplus) - Focus on BitShares mobile app.
  * [BitShares Node Admin](https://t.me/BTS_Node_Admins) - Provides server admins & interested parties with tech support.
  * [BitShares Traders](https://t.me/Bitshares_Traders) - Focus on Trading.
  * [BitShares Wallet Help](https://t.me/btsWalletHelp) - Web-based wallet & desktop wallet support.
  * [PyBitShares](https://t.me/pybitshares) - Focus on python-bitshares development.
  * [BeetApp](https://t.me/beetapp) - Focus on beetapp development.
  * [DEXBot](https://t.me/DEXBOTbts) - Focus on DEXBot development.
  * Committee - (invite only) For committee members.
  * Developers - (invite only) For developers.
  * Witnesses - (invite only) For block producers.
* [Discord - BitShares](https://discord.gg/NU2G2jrByq)

### News

* [News.BitShares.org](https://news.bitshares.org/)

### Conferences

* [Decentralized 2019 - BitShares as Event Partner](https://decentralized.com/) - In Athens, Greece.
* [Bitfest 2018](https://hive.blog/@bitfest) - in Amsterdam, Netherlands.
* [Graphene DevCon 2018](https://hive.blog/graphene/@jademont/global-graphene-blockchain-devcon-is-successfully-concluded) - in Shanghai, China.

## Utilities

### Downloads

* [BitShares-Core](https://github.com/bitshares/bitshares-core/releases) - full node and command line tools
* [BitShares-UI](https://github.com/bitshares/bitshares-ui/releases) - desktop light wallet
* [BitShares Mobile App](https://app.btspp.io/) - iOS and Android
* [Media Kit](https://github.com/bitshares/marketing/tree/master/media-kit) - Logos, banners and etc

### Blockchain API

Given that many businesses and community members operate their own API
endpoints, duplicating that list here would be unecessary efforts. Hence,
we here link to the list of nodes as used in the reference wallet on
wallet.bitshares.org.

* [List of Blockchain API endpoints](https://github.com/bitshares/bitshares-ui/blob/develop/app/api/apiConfig.js#L128)

### Extended APIs

There are some extended APIs provided by the community.

* https://api.bitshares.ws/docs/
* https://api.bitshares.build/api-docs/
* https://cryptofresh.com/api/docs
* https://xbts.io/api/

### Kibana and ElasticSearch Endpoints

Kibana and ElasticSearch endpoints can be used to query blockchain data and perform visualizations.

* kibana.bitshares.eu Down for maintenance.
* [kibana.bts.mobi](https://kibana.bts.mobi/) (and [es.bts.mobi](https://es.bts.mobi/bitshares-*/data/_count?pretty=true) for raw data).

### Opensource Wallets

* [BTS++](https://btspp.io/) - native Android/iOS app.
* [BiTSy](http://www.BiTSy-wallet.com) - native Android wallet with Merchants/Tellers map, in 104 languages.
* [Beet](https://github.com/bitshares/beet/) - standalone web application.
* [Reference Wallet](https://github.com/bitshares/bitshares-ui) - reference web wallet (ReactJS).
* [Community UI](https://github.com/bitshares/bitshares-community-ui) - fully responsive community web wallet (VueJS).
* [Citadel Desktop Wallet](https://github.com/jhtitor/citadel) - desktop wallet written in Python
* [Ledger App](https://github.com/bitshares/ledger-app-bitshares) - Bitshares Wallet App for Ledger Nano S

### Hosted Wallets

**Warning**: Since these are hosted wallets, they may have access to your
private account credentials and thus, your funds may be at risk. Do your own
research!

#### Hosted Mainnet Wallets

* [wallet.bitshares.org](https://wallet.bitshares.org) - BitShares.org hosted reference wallet, lastest release.
* [staging.bitshares.org](https://staging.bitshares.org) - BitShares.org hosted reference wallet, latest release candidate.
* [develop.bitshares.org](https://develop.bitshares.org) - BitShares.org hosted reference wallet, latest in-development version.
* [wallet.bitshares.eu](https://wallet.bitshares.eu) - BitShares Europe hosted reference wallet (customized).
* [m.magicw.net](https://m.magicw.net/) - Web version of the MagicWallet Android/iOS app.
* Check the [Exchanges](#exchanges) running on the BitShares blockchain too.

#### Hosted Testnet Wallets

* [test.xbts.io](https://test.xbts.io/)
* testnet.bitshares.org - down for maintenance.
* testnet.bitshares.eu - down for maintenance.

### Blockchain Explorers

* [BTS.ai](https://bts.ai) - closed source.
* [cryptofresh.com](https://cryptofresh.com) - closed source, operational since 2015.
* [blocksights.info](https://blocksights.info) - closed source, an improved version of open-explorer.
* bitsharescan.com - closed source. Down for maintenance.
* open-explorer.io - Down for maintenance. Open souce, code is [here](https://github.com/bitshares/open-explorer).
* bitshares-explorer.io - based on open-explorer, closed source. Down for maintenance.

## Libraries

Libraries capable of communicating with the BitShares blockchain.

### C++ Libraries

* [bitshares-core](https://github.com/bitshares/bitshares-core) - reference code base that operates the blockchain.

### Go Libraries

* [bitshares-go](https://github.com/scorum/bitshares-go) - BitShares golang client
* [go-bitshares](https://github.com/denkhaus/go-bitshares) - API for BitShares - supports websocket RPC & Wallet functions

### Java Libraries

* [graphenej](https://github.com/Agorise/graphenej) - Graphene Java lib for mobile app Developers.

### JavaScript Libraries

* [bitsharesjs](https://github.com/bitshares/bitsharesjs) - used by reference wallet.
* [btsdex](https://github.com/scientistnik/btsdex) - alternative javascript library.
* [vuex-bitshares](https://github.com/TrustyFund/vuex-bitshares) - used by Trusty/Community UI.

### Python Libraries

* [python-bitshares](https://github.com/bitshares/python-bitshares) - full featured python library.

### PHP Libraries

* [bitshares-php](https://github.com/Codaone/bitshares-php) - A php library, for reading bitshares blockchain

### Tools and Scripts

* [DEXBot](https://dexbot.info) - Market Maker bot
* [extinction-event](https://github.com/litepresence/extinction-event) - bitsharesQUANT Distributed Exchange Algo Trading Framework
* [bitshares-scripts](https://github.com/bitfag/bitshares-scripts) - a set of python scripts.
* [bitshares-tradehistory-analyzer](https://github.com/bitfag/bitshares-tradehistory-analyzer) - a set of scripts for exporting and analyzing trading history.
* [StakeMachine](https://github.com/xeroc/stakemachine) - Trading Bot Infrastructure for the BitShares Decentralized Exchange (DEX).
* [Uptick](http://docs.uptick.rocks) - command line tool.
* [Telegram notifier](https://github.com/Codaone/BitShares-Telegram-notifier) - a simple bitshares telegram notifier
* [PoolTool](https://github.com/iamredbar/PoolTool) - A simple GUI tool to help anyone use Liquidity Pools on the BitShares blockchain.

## Projects Using the BitShares Blockchain

**Warning**: Being listed here is **not endorsement** nor does it provide any
credibility to these projects. Even though the authors of this list have high
quality standards, limited resources prevent them from keeping this list
up-to-date with respect to their credibility. Use this list at your own risk and
do your own research!

### Exchanges

* Citadel `https``://citadel.li/` outdated
* [DelionDEX](https://dex.delion.online)
* [GDEX](https://www.gdex.io/)
* [ioBanker](https://iobanker.com/)
* [RuDEX](https://rudex.org/)
* [WALLDEX](https://walldex.pro/)
* [XBTS](https://xbts.io/)

### Bridges

* [BlockTrades](https://blocktrades.us/)
* [Exolix](https://exolix.com/)
* [GoDex](https://godex.io/)
* [SimpleSwap](https://simpleswap.io/)
* [StealthEx](https://stealthex.io/)
* [SwapSpace](https://swapspace.co/)

### Services

* [BTSabc](http://www.btsabc.org/)
* [Lykke](https://www.lykke.com/)
* [PalmPay](https://PalmPay.io) - A chain-agnostic Point Of Sale system, using Bitshares DEx, in 104 languages.
* [Quintric](https://quintric.com/)
* [Moneda Par](https://monedapar.com.ar/) - a non-profit based in Argentina that allows the exchange of goods and services through mutual loans.

### Games

* [SmartHoldem](https://dexgames.net/) 

## Other Blockchains in the BitShares Family

BitShares being the first that is build on the Graphene or graphene-like base
system, other blockchains have been deployed that make use of the very same
foundations:

* [Crypviser](https://crypviser.network/)
* [Cybex](https://cybex.io/en)
* [EOS](https://eos.io/)
* [Golos](https://golos.io/)
* GreenPower `https``://grnpower.io/` currently down - formerly known as `Dascoin` (`https``://dascoin.com/`).
* [Hive](https://hive.io/)
* [OmniCoin](https://omnicoin.net/)
* [Peerplays](https://www.peerplays.com/)
* [SOUNDAC](https://soundac.io/)
* [Scorum](https://scorumcoins.com/en-us/)
* [Serey](https://serey.io/)
* [Smoke Network](https://smoke.network/)
* [Steem](https://steempeak.com/)
* [VIT](https://vicetoken.com/)
* [Whaleshares](https://whaleshares.io/)
* [Yoyow](https://yoyow.org/index_en.html)

# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


To the extent possible under law, [Dr.-Ing. Fabian
Schuh](https://github.com/xeroc) has waived all copyright and related or
neighboring rights to this work.
