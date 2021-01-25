---
aip: 8
title: Aave V1 -> V2 transition plan, Phase 1
status: WIP
author: Marc Zeller (@marczeller)
discussions: https://governance.aave.com/t/aave-protocol-v1-v2-migration-tool-and-transition-plan/2053
created: 25.01.2021
updated: 25.01.2021
---

## AIP rationale

Aave V2 was launched on Dec 3 and has shown exceptional resiliency.

No particular issues were found during the launch, and after 40 days is now securely holding 750 Millions of fund and already issued 30M in flashloans, mostly thanks to the repay with collateral and swap features.

Users in V2 enjoy these new possibilities and substantially lower gas prices. Now that V2 has shown enough resiliency to safely hold a sizeable amount of funds, it’s time to start the transition from Aave V1 to Aave V2.

As discussed in the dedicated governance thread, the transition will be rolled out in several phases.

Phase 1 will disable borrowing ability on V1 for the following assets : 
BUSD, SUSD, ETH, YFI, BAT, REN, ENJ, KNC, LINK, MANA, MKR, REP, SNX, WBTC, ZRX.

Stable rates will be disabled on DAI,USDC,USDT and only variable rates will be available on these assets.

## AIP content in short

- disable borrowing ability on V1 for the following assets : 
BUSD, SUSD, ETH, YFI, BAT, REN, ENJ, KNC, LINK, MANA, MKR, REP, SNX, WBTC, ZRX
- Stable rates will be disabled on DAI,USDC,USDT


## Implementation details

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
