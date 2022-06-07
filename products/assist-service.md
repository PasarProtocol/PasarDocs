---
description: >-
  A backend service to speed up the process to retrieve on-chain NFT data, but
  can be deployed in multiple points.
---

# Assist Service

Currently, in Pasar architecture design, an user would make transactions on webApp and send signed transaction to Pasar contracts next via Wallet like Essentials or Metamask with user's authorization. While trying to load NFT data originally from Pasar contracts onto WebApp, the NFT datum are actually not directly from Pasar contracts. Instead, they are all from assist service.&#x20;

The assist services are kinds of persistent cached system for all on-chain data or even immutable off-chain data from IPFS storage network. Since the granularity of on-chain data are not always suitable for directly displaying on front-end. It would require necessary reorganizing process or even splitting/recombination process on front-end if we directly use the data from Pasar contracts. Therefore, it will take much time to process and display them, which leads to bad experience with worse response.&#x20;

Overall, the assist service would keep monitoring events from the Pasar contracts, and synchronize the NFT data and also retrieve metadata from JSON documents on IPFS as immutable data.  All NFT data including metadata would be reorganized and stored onto mongoDB in this server.  Then the assist service would provide the regonized data to frontend App to displaying on webpage or application.

And we also have long term to build a decentralized reputation system, and reputation level would be calculated most partly based on the data from Pasar contracts and IPFS network, those are immutable data and can be verified and traced.&#x20;

Besides, Assist service can be decentralized architectured, which means anyone can deploy the assist service to provide service for other users and later would be get rewards by providing such services when time is ready.
