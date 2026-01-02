# UNIT Protocol (UNIT)

UNIT Protocol is a BEP-20 utility token on BNB Smart Chain, focused on transparent on-chain mechanics, configurable tokenomics, and future product integrations.

This repository reflects the **current on-chain state** of the UNIT Protocol smart contract.

---

## Official Links
- Website: https://unitprotocolofficial.github.io/unit-site/
- Whitepaper (PDF): ./UNIT_Protocol_Whitepaper_Final.pdf
- Pitch Deck (PDF): ./UNIT_PitchDeck.pdf

---

## On-chain Details
- Network: BNB Smart Chain (BEP-20)
- Contract Address: `0x4f5710c96C446b133C59Af006A366d07414B52a9`
- Token Name: UNIT Protocol
- Symbol: UNIT
- Decimals: 18
- Max Supply: 1,000,000,000 UNIT (minted at deployment)

---

## Tokenomics (On-chain, Configurable)

The UNIT Protocol contract includes **configurable on-chain mechanics**:

- **Transaction Fees (Basis Points)**
  - Burn fee: configurable (initially set on-chain)
  - Treasury fee: configurable (initially set on-chain)
  - Combined fees are capped on-chain (cannot exceed 10%)

- **Treasury**
  - Treasury address is configurable by the contract owner
  - Treasury receives the treasury portion of transaction fees

- **Anti-Whale Protection**
  - `maxTxAmount` is enforced on-chain
  - Limits the maximum amount transferable per transaction
  - Value is configurable by the contract owner

- **Fee & Limit Exemptions**
  - Specific addresses can be exempt from fees
  - Specific addresses can be exempt from max transaction limits

> ⚠️ Important:  
> Fees are **not fixed at 0%**. They are **configurable on-chain** and may change via owner transactions.

---

## Ownership Status

- Contract ownership is **ACTIVE**
- Owner has the ability to:
  - Update fees (within hard-coded limits)
  - Update treasury address
  - Update anti-whale transaction limit
- Ownership **has NOT been renounced** at this stage

Any future ownership changes will be visible and verifiable on-chain.

---

## Liquidity

- Liquidity has been added on PancakeSwap (BNB Smart Chain)
- Liquidity provider (LP) tokens are **locked**
- Lock details (amount and unlock date) are verifiable on-chain via the LP lock platform

---

## Utility (Planned & High-level)

UNIT Protocol is designed to support:

- Token-gated access (content, memberships, services)
- Governance signaling (non-binding, off-chain or on-chain signaling)
- Reward and loyalty mechanisms
- Future integrations with DeFi and Web3 services

No guarantees are made regarding future development timelines.

---

## Transparency Notes

- The smart contract is verified on BscScan
- All parameters (fees, limits, ownership actions) are publicly visible on-chain
- No private keys, seed phrases, or sensitive credentials are contained in this repository

---

## Risk Disclosure

UNIT is an experimental digital asset.

Nothing in this repository, website, or documentation constitutes:
- Financial advice
- Investment advice
- Legal advice
- Tax advice

Cryptocurrencies are volatile and may lose all value.  
Always verify contract data directly on-chain and perform your own research before interacting.

---

## License

All content is provided **as-is**, without warranties of any kind.  
Use at your own risk.
