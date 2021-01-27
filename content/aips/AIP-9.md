---
aip: 9
title: Activation of the Balancer Pool Liquidity Staking
status: WIP
author: Marc Zeller (@marczeller)
discussions: https://governance.aave.com/t/arc-aavenomics-quarterly-upgrade/1631
created: 2021-01-27
updated: 2021-01-27
---

## AIP rationale

As stated in the [Aavenomics paper](https://aave.com/Aavenomics.pdf), the AAVE asset is designed to become the center of gravity for Aave governance and the protocol safety, The Safety Incentives (SI) allocation is designed to incentivize the lines of defenses of the Aave protocol.

AIP-1 was the first step of the activations of the lines of defenses of the Aave Protocol with the activation of the safety module, for the Safety to be as efficient as possible, it is required to reach significant liquidity of the AAVE asset on a Decentralized AMM.

This AIP aims at incentivizing the Liquidity providing for the AAVE asset on a specificaly designed smart pool of the Balancer protocol to make the AAVE asset more liquid on-chain by activation Safety Incentives (SI) for BPT tokens stakers.

BPT tokens can be obtained by providing liquidity to the AAVE/ETH Balancer smart pool at a 80/20 ratio.

This AIP, if accepted by the community, will start the Safety Incentive (SI) rewards distribution for BPT stakers at the rate of 550 AAVE/day.

The Safety Module is designed as an additional line of defense for Aave protocol liquidity providers and Both highliquidity and Safety module reserve can mitigate the possibility of bad debt in the occurence of a shortfall event.

## AIP content in short

- upgrade of the quarterly plan of Safety Incentives (SI) allocation
- Start of the Safety Incentives for BPT stakers with initial SI rewards of 550 AAVE/day

## Safety Incentives Schedule

If the community accepts the current AIP, the Safety Incentives quarterly program will be upgraded to

- 550 AAVE/day to the Safety Module Stakers
- 550 AAVE/day to the BPT tokens Stakers

For a total of 1100 AAVE/day Safety Incentives allocation.

The Safety Incentive's allocation quarterly date should be voted on before the end of the 3 months (90 days) distribution schedule. In the case of a late or no vote on a new SI allocation plan, the current allocation will continue until a vote or until the ER is empty.

## Implementations details

[CHANGE THIS]

If this AIP is validated by a community vote, the following addresses will be involved in the migration process :

- [0x95a4949f09415b12da789e144b2522956620d005](https://etherscan.io/address/0x95a4949f09415b12da789e144b2522956620d005) AaveGenesisPayloadProposal : Contract in charge of enforcement of the AIP outcome
- [0xa133459b2502b0137e85a446fa8d4e300877a007](https://etherscan.io/address/0xa133459b2502b0137e85a446fa8d4e300877a007) AaveGenesisExecutor : Contract enforcing a 24h delay on enforcement of AIP outcome to allow the community to be prepared to migrate
- [0x25f2226b597e8f9514b3f68f00f494cf4f286491](https://etherscan.io/address/0x25f2226b597e8f9514b3f68f00f494cf4f286491#code) AaveIncentivesVault : Ecosystem Reserve
- [ADD BPT POOL]

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
