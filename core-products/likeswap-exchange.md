---
description: LikeSwap AMM (Automated Market Maker) Decentralized Exchange
---

# 💱 Exchange

### Contracts

* Factory: [0xcedb8a736b666a90182a270a016bd7d3114fe9da](https://bscscan.com/address/0xcedb8a736b666a90182a270a016bd7d3114fe9da#code)
* Router: [0xed8562b9421edb330ffc46be88eceecbb29a5c06](https://bscscan.com/address/0xed8562b9421edb330ffc46be88eceecbb29a5c06#code)
* INIT\_CODE\_PAIR\_HASH: 0x008d9fe3bb37e31c0da6c6a40a7712cc03931bd7be4f514d20a188ab638be25c

The LikeSwap AMM exchange v1 is a complete fork of PancakeSwap, the factory & router smart contracts are the same as PancakeSwap (we only changed "pancake" to "like" in these two contracts). It means that the contracts where store liquidity (your money) are as safe as PancakeSwap.

You can use the links below to compare the smart contracts of LikeSwap and PancakeSwap.

[![](../.gitbook/assets/image.png) **Diffchecker**](https://www.diffchecker.com/8XQj0kyB)****

[![](../.gitbook/assets/image.png) **Diffchecker**](https://www.diffchecker.com/YRWOSKVt)****

****

### Trading Fee

[**Token swaps**](https://app.likeswap.org/#/swap) on LikeSwap are a simple way to trade one BEP-20 token for another via automated liquidity pools. In the backend of the exchange we are using [LikeSwap](https://likeswap.org).

![LikeSwap Exchange UI](../.gitbook/assets/likeswap-exchange.png)

The liquidity provided to the exchange comes from Liquidity Providers ("LPs") who stake their tokens in "Pools". In exchange, they get FLIP (LikeSwap Liquidity Provider) tokens, which can also be staked to earn LIKE tokens in the "farm".

![LikeSwap Pools UI](../.gitbook/assets/liquidity.png)

When you make a token swap (trade) on the exchange you will pay a **0.2% trading fee**, which is broken down as follows:

**0.17%** - Returned to liquidity pools in the form of a fee reward for liquidity providers.

**0.03%** - Sent to the LikeSwap Treasury.
