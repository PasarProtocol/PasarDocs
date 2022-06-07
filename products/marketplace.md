---
description: >-
  A general marketplace where users can trade NFTs with fixed price or on
  auction.
---

# Marketplace

A new advanced PasarV2 marketplace is living now, where users can list NFTs in two different methods:

* list NFT with fixed price.  In this case, users can directly buy the NFT with requested price, and after the transactions succeeds, the buyer will get the NFT
* list NFT on auction. A seller list it on marketplace on auction, and users can make bidding on it when they likes it and want to buy it. Once the expiration arrived, or buyout price meet, then the winner will get this NFT

There are more features in PasarV2 marketplace:

* Users can list NFTs in ERC20 token price other than ELA.  A list of supported ERC20 token so far includes:&#x20;
  * WELA/ETH (wrapper tokens)
  * GLIDE/ELK (DEX tokens)
  * USDC/BUSD (Stable pegged tokens)
  * DIA (Pasar boost token)
  * BUNNY  (The first ERC20 token for dedicated collection)
* Rich features for auction listing. Basic users can list NFT with basic auction mechanism, in which users can make bidding on the auciton and have to wait for the acuiton expiration. To advanced users with more DIA holding, the seller can list NFT on auciton with reserve price and buyout price supported.  When a reserve price is offered on auciton, then if the winner biding price is less than reserve price, then auction would not be filled after the auction is expired.  And if a buyout price is offered, then once an users make a bidding price equal or higher than buyout price, then the auction would be fulfilled immediately. And this user will win the auction and own the NFT then.

