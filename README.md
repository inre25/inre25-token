# INRE25

INRE25 is a TON Jetton public proof package for the INRE25 token.

This repository is prepared as a public proof package before DEX pool work and catalog submissions. It is not a confirmation of any wallet, explorer, catalog, or DEX listing.

## Overview

INRE25 is presented as a TON Jetton utility token connected with the INRE25 public website and public tokenomics materials.

This package collects public token identity data, official public links, logo files, and public PDF documents. It does not contain backend source code, private operational data, user data, or secrets.

## Official Links

- Official site: https://inre25.com/
- Token info: https://inre25.com/token-info/
- Tokenomics: https://inre25.com/tokenomics/
- Tokenomics docs page: https://inre25.com/docs/tokenomics/
- Economy model docs page: https://inre25.com/docs/economy-model/
- Sitemap: https://inre25.com/sitemap.xml
- GitHub: https://github.com/inre25/inre25-token

## Token Identity

- Project/token name: INRE25
- Symbol: INRE25
- Network: TON
- Standard: TON Jetton
- Decimals: 9

## Jetton Master

```text
EQCP-D1tfJ8MDlsk9MWQXNjP9_0mxwXNVNvH_IWhobfyQLUq
```

Explorer and catalog links should be verified again before final submission.

## Public Documents

- Tokenomics Whitepaper: `docs/INRE25_Tokenomics_Whitepaper.pdf`
- Platform Economy Model: `docs/INRE25_Platform_Economy_Model.pdf`

## Tokenomics Summary

Public website materials currently describe:

- Initial mint: 100,000,000,000 INRE25
- Initial burn: 75,000,000,000 INRE25
- Total supply: 25,000,000,000 INRE25
- Start pricing anchor: 1 INRE25 = 0.0025 USDT
- Start pricing ratio: 1 USDT = 400 INRE25
- Launch pool target: 1,000,000 INRE25
- Launch pool value at launch: 2,500 USDT
- If a public DEX pool is created, market price may be formed by public DEX trading conditions

This repository does not claim that a DEX pool already exists.

## Public Updates and Supply Notes

This repository is not a chronological news log.

Official public project updates, including supply-related announcements, liquidity notes, technical lock notes, burn notes, and other project updates, are published through the official INRE25 website and the official Telegram news channel:

https://t.me/inre25_official

Technical Lock is a public tokenomics mechanism used to identify INRE25 moved out of effective available circulation through a publicly verifiable on-chain address or technical mechanism described in the official project materials.

Technical Lock is used for public verifiability and for easier observation of the INRE25 amount excluded from effective available circulation.

According to the verified Jetton Master contract code and the official project materials, the Technical Lock address is not intended to operate as a regular user wallet for managing received INRE25 as a normal user balance.

The verified contract code does not provide a function that would allow developers, the project owner, or third parties to:

- withdraw those INRE25 back;
- transfer them to another address;
- manage them as a regular user balance.

INRE25 moved to Technical Lock remains publicly visible on-chain, but is excluded from effective available supply and from the project's accessible circulation.

Technical Lock is not a standard burn event and does not reduce the on-chain total supply. Its purpose is to provide public visibility for INRE25 excluded from effective available supply and to support tokenomics discipline.

Technical Lock must not be interpreted as a promise of token price growth.

The public tokenomics documents linked in this repository remain the reference materials for the current published tokenomics model.

## Repository Contents

- `assets/logo/` - public INRE25 logo and icon files.
- `docs/` - public PDF documents linked by the website.
- `metadata/` - notes for pending token metadata work.
- `token-info/` - public token address and official link notes.
- `SECURITY.md` - public information safety notice.

## Security / Public Information Notice

This repository is intended to contain only public INRE25 information. It must not contain private keys, mnemonics, API keys, environment files, database dumps, runtime files, user data, admin material, or operational secrets.

If sensitive data is found, publication must stop and the repository must be reviewed before any push.

## Pending Public Metadata Items

- Final token metadata JSON will be added after checking target catalog/schema requirements.
- Final GitHub URL will be added after repository publication.
- Final external explorer/catalog requirements are pending.
- `metadata/token.json` is intentionally not included yet.
