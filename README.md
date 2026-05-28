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
- GitHub URL: will be added after publication

## Token Identity

- Project/token name: INRE25
- Symbol: INRE25
- Network: TON
- Standard: TON Jetton
- Decimals: 9
- Primary logo for catalog/metadata later: `assets/logo/512x512.png`
- Reserve large logo: `assets/logo/1024x1024.png`
- SVG logo for README/brand use: `assets/logo/inre25.svg`

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

## Technical Lock Note

The 500,000,000 INRE25 operation dated January 25, 2026 is a Technical Lock, not a burn. It does not reduce the on-chain total supply, but it removes those tokens from effective available circulation.

The primary burn of 75,000,000,000 INRE25 remains a separate burn event.

Technical Lock references should be checked against public explorers before final catalog or DEX submission.

## Repository Contents

- `assets/logo/` - public logo and icon files copied from the public website assets.
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
