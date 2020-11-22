# 💻 Developer Resources

### Summary

* [Stellar Dev Digest](https://stellar.us9.list-manage.com/subscribe?u=c001d97369b7a10d224c23867&id=e1f435dc0a) - Weekly newsletter covering all things around the Stellar developer ecosystem.
* [Stellar Github](https://github.com/Stellar)
* [Stellar Core](https://github.com/stellar/stellar-core) - stellar-core is the backbone of the Stellar network. It maintains a local copy of the ledger, communicating and staying in sync with other instances of stellar-core on the network.
* [Astrocore](https://github.com/astroband/astrocore) - Astrocore aims to become an alternative implementation of the stellar-core, the core component of the Stellar network.
* [Stellar Protocol](https://github.com/stellar/stellar-protocol) - Developer discussion about possible changes to the protocol.
  * [Stellar Ecosystem Proposals](https://github.com/stellar/stellar-protocol/blob/master/ecosystem/README.md) 
  * [Core Advancement Proposals](https://github.com/stellar/stellar-protocol/blob/master/core/README.md)
* [Stellar Docs](https://developers.stellar.org/docs/) - Stellar documentation.
* [Stellar Laboratory](https://www.stellar.org/laboratory/) - The Stellar Laboratory is a set of tools that enables people to try out and learn about the Stellar network.

### Stellar SDKs

* [JavaScript SDK](https://www.stellar.org/developers/js-stellar-sdk/reference/) 
* [Go SDK](https://www.stellar.org/developers/go/reference/)
* [Java SDK](https://github.com/stellar/java-stellar-sdk)
* [Kotlin SDK](https://github.com/Inbot/inbot-stellar-kotlin-wrapper)
* [Python SDK](https://github.com/StellarCN/py-stellar-base) 
* [C\# .NET Core 2.0 SDK](https://github.com/elucidsoft/dotnet-stellar-sdk) 
* [Ruby SDK](https://github.com/astroband/ruby-stellar-sdk)
* [iOS and macOS SDK](https://github.com/Soneso/stellar-ios-mac-sdk)
* [Scala SDK](https://github.com/synesso/scala-stellar-sdk)
* [C++ SDK](https://github.com/bnogalm/StellarQtSDK)
* [Unity C\# SDK Integration](https://github.com/Kirbyrawr/stellar-unity)
* [Flutter SDK](https://github.com/Soneso/stellar_flutter_sdk)

### Interact with the Stellar Network

* [Horizon API](https://horizon.stellar.org/) - Horizon allows you to submit transactions to the network, check the status of accounts, and subscribe to event streams. Servers hosted in the US.
  * [Horizon Github Repo](https://github.com/stellar/go/tree/master/services/horizon) 
* [SatoshiPay's Horizon API](https://stellar-horizon.satoshipay.io/) - SatoshiPay's alternative to Stellar.org's Horizon API servers. Servers hosted in the US, Europe, and Asia.
* [Astrograph](https://astrograph.io/) - A GraphQL interface to the Stellar network.
  * [Astrograph Github Repo](https://github.com/astroband/astrograph) 
* [go-stellar-ipfs](https://github.com/aanupam23/go-stellar-ipfs) - A library that is a bridge between Stellar and IPFS.
  * [go-stellar-ipfs Github Repo](https://github.com/aanupam23/go-stellar-ipfs)
* [Stellar Ticker API](https://ticker.stellar.org/) - Provides the freshest data about Markets, Issuers and Assets on the Stellar Network.
  * [GraphiQL for Stellar Ticker](https://ticker.stellar.org/graphiql) - an in-browser tool for writing, validating, and testing GraphQL queries.
  * [Ticker API Documentation](https://github.com/stellar/go/blob/master/services/ticker/docs/API.md) 
  * [Assets Endpoint](https://ticker.stellar.org/assets.json) - Displays information about all assets available. 
  * [Markets Endpoint](https://ticker.stellar.org/markets.json) - Displays 24-hour, 7-day and orderbook information about markets that were active during these periods. 
* Useful Tools
  * [Hack Stellar Boilerplate](https://github.com/tyvdh/hack-stellar) - This Hack Stellar app is a boilerplate collection of basic Stellar functions. You can either hack this Stencil project into whatever you're trying to build or just cut and paste out the functions from here into your own project.
  * [StellarBurrito](https://github.com/stellarburrito/stellarburritojs) - An open-source wrapper for the JavaScript Stellar SDK. 
  * [Stellar Vanity Address Generator](https://github.com/robertDurst/stellar-vanity-address-generator) - A simple CLI tool to generate custom Stellar vanity addresses. 
  * [Stellar transaction signers inspector](https://github.com/stellar-expert/stellar-tx-signers-inspector) - Discover required signers, weights, and build optimal signature schema for Stellar transactions and accounts.
  * [Cosmic.plus libraries](https://cosmic.plus/#libraries)
    * cosmic-lib: implement CosmicLink & SEP-0007.
    * ledger-wallet: Ledger Wallets support in two lines of code.
    * loopcall: Limitless/advanced queries to horizon.
    * oc-multisig: On-chain multisig account coordination.
  * [Create Stellar Token \(Testnet\)](https://github.com/msfeldstein/create-stellar-token) - Script that creates a custom Stellar token on testnet. 
  * [Cosmic.link SEP-0007 debugger](https://cosmic.plus/js-cosmic-lib/web/demo) 
  * [Cosmic.plus applications](https://cosmic.plus/#applications)
    * Equilibre.io: wallet-independent portfolio balancer for Stellar \(first app to use delegated signing\)
    * Cosmic.link: CosmicLink protocol frontend.
    * Stellar Authenticator: Security-oriented wallet. \(+ useful dev tool\)
* Validator Tools
  * [Fast Stellar Core Catch Up](https://github.com/Lobstrco/stellar-core-parallel-catchup-py) - Starting a full stellar core validator from scratch takes a while, as the node needs to download and process a lot of data during the "Catch up" phase. The catching up phase usually takes more than a month. This script helps to make the process significantly shorter, as it allows to perform the catch up of multiple ledgers blocks in parallel.
  * [Parallel Stellar Core Catchup](https://github.com/satoshipay/stellar-core-parallel-catchup) - Sync a full Stellar validator node \(including full history\) as fast as possible. Split the big ledger into small chunks of size CHUNK\_SIZE. Run a catchup for the chunks in parallel with WORKERS worker processes. Stitch together the resulting database and history archive.
  * [Stellar Parallel Catchup](https://github.com/astroband/stellar-parallel-catchup) - Catchup Stellar node history in background. 

### Developer Educational Resources

* [Developer Guides and Concepts](https://www.stellar.org/developers/guides/) - These guides are designed to help you learn more about the technical aspects of integrating Stellar into your application or service.
  * [How and Why to Complete Your Stellar.toml](https://www.stellar.org/developers/guides/walkthroughs/how-to-complete-stellar-toml.html)
  * [How to Connect Your Anchor Service to Stellar Wallets](https://www.stellar.org/developers/guides/walkthroughs/connect-to-wallets.html) 
  * [Creating Custom Assets on Stellar](https://www.stellar.org/developers/guides/walkthroughs/custom-assets.html) 
* [How Stellar.org Recovers From a Testnet Reset](https://www.stellar.org/developers/blog/how-stellar-org-recovers-from-a-testnet-reset)
* [Get Started Building Stellar Applications: New York Blockchain Week Hackathon](https://youtu.be/kDzIpKXOdf0)
* [Fee Bump Transactions Explained](https://medium.com/stellar-community/fee-bump-transactions-explained-9a6a365c0fb6) - A look at transactions on Stellar, the costs involved in submitting them,problems that could arise submitting transactions pre-Protocol 13, and how fee bump transactions solve them.
* [Stellar Developer Workshop with Tomer Weller](https://youtu.be/80FKQeghK_4)
* [Building your own Venmo with Stellar](https://blog.abuiles.com/building-your-own-venmo-with-stellar/) - This tutorial will show you how to create an anchor maintaining a Stellar account for each customer, hiding the implementation details. It will use the programming language JavaScript and the mobile wallet will be written using React Native.
* [Explore Stellar Addresses and the Stellar DEX using Python](https://medium.com/@kolten/explore-stellar-addresses-and-the-stellar-dex-using-python-e72611822b48) - In this tutorial you'll be creating a script that takes in a Stellar address and returns the XLM balance. You will also convert that XLM balance to USD using the new ticker API for the Stellar DEX.
* [Stream Ledger Data from the Stellar Network Using Python](https://medium.com/@kolten/stream-ledger-data-from-the-stellar-network-using-python-861af04c40ab)
* [Stellar payments — thoughts on federation, QR Codes, URIs, and Point of Sale systems within the Stellar.org ecosystem](https://medium.com/lumenauts/stellar-payments-thoughts-on-federation-qr-codes-uris-and-point-of-sale-systems-within-the-2c6fcdc3fa4d)
* [Sending Secret and Anonymous Memos with Stellar](https://medium.com/lumenauts/sending-secret-and-anonymous-memos-with-stellar-8914479e949b)
* [Distributed Trustless Workers with Stellar](https://medium.com/lumenauts/distributed-trustless-workers-with-stellar-e197fd1b77f6) - An in-depth look at how Stellar’s advanced features can be used to create a “smart contract” between a customer and an anonymous and untrusted worker.
* [I Just Wrote a Stellar Smart Contract](https://medium.com/@robdurst/i-just-wrote-a-stellar-smart-contract-7f54a391f5e1) & [I Just Wrote a Stellar Smart Contract Pt. 2: Let’s Dig a Little Deeper](https://medium.com/hackernoon/i-just-wrote-a-stellar-smart-contract-pt-2-lets-dive-a-little-deeper-a8dae19b9d0a) - Exploring Stellar 'smart contracts.'
* [Hacking Stellar](https://github.com/0xfe/hacking-stellar) - This online book introduces you to Stellar with lots of practical examples using the command-line client, Lumen. Incomplete but useful nonetheless for understanding basic concepts.
* Understanding the Stellar Consensus Protocol - Useful information regarding SCP.
* [How to Create a Custom Token on Stellar in Python](https://medium.com/python-pandemonium/how-to-create-a-custom-token-on-stellar-network-in-python-abf8b2f7a6f8)
* [StellarTxSignersInspector - Facilitating Multisig Discovery](https://stellar.expert/blog/stellar-tx-signers-inspector-facilitating-multisig-discovery)

### Engineering Talk Series

* [Creating Usable Stellar Applications](https://youtu.be/hVGHMkYL15s)
* [Intuitive Stellar Consensus Protocol](https://youtu.be/fDt8Eh4T_lE)
* [Kelp GUI](https://youtu.be/zxBoERxZcQs) 
* [Practical Path Payments](https://youtu.be/KzlSgSPStz8) 
* [ZkVM: about the motocrab](https://youtu.be/1i-EJykVzag) 
* [User-Friendly Key Management with SEP-30 Recoverysigner](https://youtu.be/W-n73Cuy7-0) 
* [Turing Complete Contract proposal for Stellar](https://youtu.be/T7FlHKbew4U) 

