---
aip: 1
title: LEND/AAVE migration and activation of the Safety Module
status: WIP
authors: Marc Zeller (@mzeller), Emilio Frangella (@The-3D)
discussions: https://governance.aave.com/t/initial-discussion-aave-reserve-emission-for-safety-and-ecosystem-incentives/85/60
created: 2020-09-21
---

## AIP rationale

As stated in the [Aavenomics paper](https://aave.com/Aavenomics.pdf), the AAVE asset is designed to become the center of gravity of Aave governance and protocol.


DeFi, decentralized ethos has been achieved with most protocols on the financial part, creating an ecosystem of financial applications with users in control and with true ownership of their own assets
but we think that part is only the halfway point of the Decentralization objective, users are in control of their assets, they should also be be in control of their protocol the AAVE asset is designed for this
and this AIP is the first binding step of this community ownership of the Aave protocol.


This AIP, if accepted by the community, will slowly deprecate the LEND asset in favour of the AAVE asset.
As stated in the Aavenomics, this token upgrade will also create the Ecosystem Reserve (ER) and the Safety Module (SM)
The Safety Module is designed as an addtional line of defense for Aave liquidity providers and as a way for AAVE holders to "stake" their assets in exchange of a range of rewards.


This AIP purpose is also to dedicate XX% of the ER to a kickstart incentive for the Safety module first stakers destributed during a quarter.

## AIP content in short

- Migration LEND -> AAVE asset with the migration contract
- Start of the Safety Module incentive with initial reward of 400 AAVE/day
- Increase of the rewards to XX AAVE/day after the activation of the Safety Module
- Increase of the rewards to XX AAVE/day after the activation of the Balancer Liquidity providing
- Activation of the quarterly plan of AAVE rewards allocation

## ER allocation plan

| Purpose | AAVE per day | % of the ER | Total |
|-|-|-|-|
|Safety module kickstart | 400 | xx% | xx |
|Activation of the Safety module | XXX | XXX |
|Activation of the Balancer LP program | XXX| XXX |

The Bootstrapping phase of Safety module will be a step-by-step process in 3 main phases : 
- Initial bootstraping with launch of the safety module, the ability to stake and earn AAVE rewards but no activation of the safety module and thus riskless for stakers
- Activation of the Safety Module, increase of the AAVE rewards to XX AAVE/day and new line of defense for the Aave protocol users
- Activation of the Balancer LP program, increase of the AAVE rewards to XX AAVE/day and new rewards in BAL tokens

The initial Bootstraping phase rationale is designed to have lower rewards and a riskless environement to allow the majority of LEND holders to migrate at their own pace and avoid rush sentiment while interracting with critical migrating and staking smart-contracts.
The Activation of the Balancer LP program rationale is designed to create as much as possible decentralized liquidity to the AAVE asset, allowing independance from centralized finance and attractive liquidity for the ecosystem, the recent success of Uniswap LP program with the UNI asset acts as an encouraging example of this kind of incentivization scheme. 

The ER allocation plan next quarter date should be voted before the Xx/XX/202x, in case of late or no vote on a new ER allocation plan, the current allocation will continue until a vote or ER being empty.

## AIP Editors

The current AIP editors are

`* David Truong (@mrdavey)`

`* Emilio Frangella (@The-3d)`

`* Ernesto Boado (@ernesto-usal)`

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
