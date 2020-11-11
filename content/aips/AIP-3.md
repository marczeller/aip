---
aip: 3
title: V1 upgrades for seamless transition to AAVE v2 
status: WIP
author: Marc Zeller (@marczeller)
discussions: https://governance.aave.com/t/TBA
created: 2020-11-11
updated: 2020-11-11
---

## AIP rationale

AT the time of writing, 14,732,165 aLEND are deposited in the Aave protocol reserve, several community members currently use these assets as collateral in loans and would like to migrate both from LEND to AAVE and from V1 to V2 in the future.
Outside of the situation of the aLEND holders, having a Flashloan-powered migration tool to allow seamless migration from v1 to v2 would significantly ease the process of upgrading the liquidity to the new version of AAVE.

To allow these new features, small modifications of the `repay()` method is needed to upgrade the efficiency of the process and allow v2 flashloans to access it.

## AIP content in short

- upgrade of `lendingPool` v1 smart-contract `repay()` method
- [EMILIO NEEDED] something about adapter
  
  This AIP expected effect will be the increase of migrated LEND and faster & easier transition to Aave V2 of V1 liquidity alongside an increased volume of Flashloans.


## Implementation details

- Upgrade of the LendingPool contract https://etherscan.io/address/0x398eC7346DcD622eDc5ae82352F02bE94C62d119 
- Modify the repay() function as follows:

  [EMILIO NEEDED]
  
  
## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
