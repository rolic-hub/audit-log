# Audit-Log
A list of audits participated in with learnings, and lessons on web3 security

## Summary Statistics
- **Total Competitions**: 20
- **Total Findings**: 42+
- **Platforms**: Sherlock, Cantina, CodeHawks, Code4rena, Immunefi

---

## Audit Findings

### 2025

| Date | Protocol | Platform | Rank | # | Reward | Findings |
|------|----------|----------|------|---|--------|----------|
| Nov '25 | Vechain \| Stargate Hayabusa | Immunefi | #56 | 1 | 14 USDT | Finding not yet public |
| Oct '25 | Index Fun Order Book | [Sherlock](https://audits.sherlock.xyz/contests/1197) | #11 | 2 | 45.54 USDC | Fee in trade is paid by the seller not the buyer; Rounding errors can lead to buyer receiving outcome tokens without paying collateral |
| Jul '25 | Attackathon \| Plume Network | Immunefi | #37 | 4 | 639 USDC | Findings not yet public |
| Jul '25 | succinct-network | Cantina | 🥉 | 1 | 4,926.99 USDC | Finding not yet public |
| May '25 | primev-validator-registry | Cantina | #6 | 1 | 0.18 USDC | Finding not yet public |
| Apr '25 | Burve | [Sherlock](https://audits.sherlock.xyz/contests/858) | #20 | 3 | 304.89 USDC | Double taxation in removeValueSingle; Zero fee calculation due to uninitialized removedBalance; Missing owner acceptance function |
| Apr '25 | liquidity-book-vaults | Cantina | #28 | 3 | 93.66 USDC | Findings not yet public |
| Mar '25 | PinLink: RWA-Tokenized DePIN Marketplace | [Sherlock](https://audits.sherlock.xyz/contests/852) | #22 | - | 62.25 USDC | - |
| Feb '25 | THORWallet | Code4rena | 🥉 | 1 | 346.49 USDC | User can send tokens to any address using two bridge transfers, even when transfers are restricted |
| Feb '25 | Rova | [Sherlock](https://audits.sherlock.xyz/contests/498) | 🥉 | 1 | 0.04 USDC | Arithmetic operation on userTokenAmount and refundCurrencyAmount/additionalCurrencyAmount is incorrect |
| Jan '25 | reserve-index-dtf | Cantina | #8 | 1 | 53.43 USDC | Finding not yet public |
| Jan '25 | Aave v3.3 | [Sherlock](https://audits.sherlock.xyz/contests/747) | #38 | - | 615.24 USDC | - |

### 2024

| Date | Protocol | Platform | Rank | # | Reward | Findings |
|------|----------|----------|------|---|--------|----------|
| Dec '24 | Alchemix Transmuter | CodeHawks | 🥉 | 4 | 782.99 OP | Incorrect Total Assets Calculation in _harvestAndReport; Not adding claimable balance to total assets; Inflated totalAssets in Strategy contracts; Old router retains token allowance after update |
| Dec '24 | InterPol | Cantina | #10 | 1 | 156.87 USDC | Finding not yet public |
| Oct '24 | Ethos Network Social Contracts | [Sherlock](https://audits.sherlock.xyz/contests/584) | #6 | 1 | 45.37 USDC | Removed account still has access to the profile, as EthosProfile::profileIdByAddress mapping is not deleted when deleting an account |
| Oct '24 | stakeup-bloomv2 | Cantina | #20 | 3 | 555.29 USDC | Findings not yet public |
| Sep '24 | symbioticfi-core | Cantina | #11 | 1 | 348.46 USDC | Finding not yet public |
| Sep '24 | Flayer | [Sherlock](https://audits.sherlock.xyz/contests/468) | #30 | 3 | 489.38 USDC | Contract cannot receive native token; Royalties paid on L2 for ERC1155 tokens cannot be claimed; Incorrect index of checkpoint |
| Aug '24 | Tadle | CodeHawks | #29 | 9 | 204.33 USDC | TokenManager unlimited withdraw; Taker of bid offer loss assets; Native token withdrawal fails; Incorrect access control in settleAskTaker; Formulaic error rounds down causing total loss; Multiple other issues |
| Jun '24 | Size | Code4rena | #60 | 2 | 3.48 USDC | Users won't liquidate positions because liquidator profit logic is incorrect; Multicall does not work as intended |

---

## Writeups

### Succinct audit solo writeUp:
https://x.com/heezeEth/status/1961147400216617205

---

## Platform Audit Profiles
- **Sherlock** -- https://audits.sherlock.xyz/watson/heeze
- **Cantina** -- https://cantina.xyz/u/heeze
- **CodeHawks** -- https://profiles.cyfrin.io/u/_frolic
