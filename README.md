# Audit-Log
A list of audits participated in with learnings, and lessons on web3 security

## Summary Statistics
- **Total Competitions**: 20
- **Total Findings**: 42+
- **Platforms**: Sherlock, Cantina, CodeHawks, Code4rena, Immunefi

---

## Audit Findings

### 2025

| Date | Protocol | Platform | Rank | Findings | Notable Findings |
|------|----------|----------|------|----------|------------------|
| Nov '25 | Vechain \| Stargate Hayabusa | Immunefi | #56 | 1 | Finding not yet public |
| Oct '25 | Index Fun Order Book | Sherlock | #11 | 2 | Fee in trade is paid by the seller not the buyer; Rounding errors can lead to buyer receiving outcome tokens without paying collateral |
| Jul '25 | Attackathon \| Plume Network | Immunefi | #37 | 4 | Findings not yet public |
| Jul '25 | succinct-network | Cantina | 🥉 | 1 | Finding not yet public |
| May '25 | primev-validator-registry | Cantina | #6 | 1 | Finding not yet public |
| Apr '25 | Burve | Sherlock | #20 | 3 | Double taxation in removeValueSingle; Zero fee calculation due to uninitialized removedBalance; Missing owner acceptance function |
| Apr '25 | liquidity-book-vaults | Cantina | #28 | 3 | Findings not yet public |
| Mar '25 | PinLink: RWA-Tokenized DePIN Marketplace | Sherlock | #22 | - | - |
| Feb '25 | THORWallet | Code4rena | 🥉 | 1 | User can send tokens to any address using two bridge transfers, even when transfers are restricted |
| Feb '25 | Rova | Sherlock | 🥉 | 1 | Arithmetic operation on userTokenAmount and refundCurrencyAmount/additionalCurrencyAmount is incorrect |
| Jan '25 | reserve-index-dtf | Cantina | #8 | 1 | Finding not yet public |
| Jan '25 | Aave v3.3 | Sherlock | #38 | - | - |

### 2024

| Date | Protocol | Platform | Rank | Findings | Notable Findings |
|------|----------|----------|------|----------|------------------|
| Dec '24 | Alchemix Transmuter | CodeHawks | 🥉 | 4 | Incorrect Total Assets Calculation in _harvestAndReport; Not adding claimable balance to total assets; Inflated totalAssets in Strategy contracts; Old router retains token allowance after update |
| Dec '24 | InterPol | Cantina | #10 | 1 | Finding not yet public |
| Oct '24 | Ethos Network Social Contracts | Sherlock | #6 | 1 | Removed account still has access to the profile, as EthosProfile::profileIdByAddress mapping is not deleted when deleting an account |
| Oct '24 | stakeup-bloomv2 | Cantina | #20 | 3 | Findings not yet public |
| Sep '24 | symbioticfi-core | Cantina | #11 | 1 | Finding not yet public |
| Sep '24 | Flayer | Sherlock | #30 | 3 | Contract cannot receive native token; Royalties paid on L2 for ERC1155 tokens cannot be claimed; Incorrect index of checkpoint |
| Aug '24 | Tadle | CodeHawks | #29 | 9 | TokenManager unlimited withdraw; Taker of bid offer loss assets; Native token withdrawal fails; Incorrect access control in settleAskTaker; Formulaic error rounds down causing total loss; Multiple other issues |
| Jun '24 | Size | Code4rena | #60 | 2 | Users won't liquidate positions because liquidator profit logic is incorrect; Multicall does not work as intended |

---

## Writeups

### Succinct audit solo writeUp:
https://x.com/heezeEth/status/1961147400216617205

---

## Platform Audit Profiles
- **Sherlock** -- https://audits.sherlock.xyz/watson/heeze
- **Cantina** -- https://cantina.xyz/u/heeze
- **CodeHawks** -- https://profiles.cyfrin.io/u/_frolic
