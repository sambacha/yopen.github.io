---
title: "Ecosystem"
date: 2020-11-28T15:15:26+10:00
featured: true
draft: false
weight: 3
---

Yearn Finacne Ecosystem

## Protocol Layer Integrations

Risks Identified

    A protocol such as Aave Lending Pool Core has a contract failure
    Problems withdrawing from a lending protocol used to borrow against collateral. This happens when too much of a supplied asset has been borrowed (it has happened on other lending protocols).
    Admins of DeFi protocols that are not fully decentralised make unexpected changes to the protocols that adversely affect Yearn products.

Why is each a risk?

    YFI is built on top of other DeFi protocols. Problems with these protocols can causes losses to people using YFI products.
    People deposit in vaults with the expectation that they can withdraw their funds at any time. If they are stuck on a lending protocol then this can lead to reputational risk.
    Many DeFi protocols are not yet fully decentralised. This is because they are mostly not in a finished state and the team wants the ability to make sudden changes if necessary. These DeFi protocols are often transitioning to full decentralisation.

How is this risk mitigated?

    If they are stolen maliciously then they can be blacklisted. If they get sent to a burn address they will be gone forever. A good risk management framework would consider how to deal with these situations before they arise.
    Only lending protocols with well managed liquidity are used by YFI products. YFI does not accept this risk.
    Protocols that are considered too risky are not used by YFI. Protocols that are currently too risky but may be used in the future are being monitored (e.g. For.Tube or Cream.Finance). YFI aims to use the least risky protocols in the DeFi space.

The following links are useful for understanding the risk frameworks of the protocols with which Yearn Finance interacts.

Aave
https://docs.aave.com/risk/

Compound Finance
https://compound.finance/docs/security#economic-security

MakerDAO
https://blocking.net/2863/20000-words-to-understand-the-risk-management-framework-of-makerdao/
