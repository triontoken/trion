# TRION Token Metadata & Brand Assets

Official public asset package for TRION on Solana.

## Verified identity

- Name: TRION
- Symbol: TRION
- Network: Solana Mainnet
- Standard: SPL Token
- Mint: `8VuCMJWD3QaL52nwPQE7bBkR93p7HZnxButb6KGNd6oe`
- Decimals: 9
- Maximum and current supply: 1,000,000,000 TRION
- Mint authority: permanently revoked
- Freeze authority: none
- Website: https://triontoken.com

## Package structure

- `assets/logo.png` - primary wallet logo, 256 x 256 PNG, circular presentation, under 100 KB.
- `assets/logo-512.png` - high-resolution wallet and tracker logo.
- `assets/trion-mark-transparent.png` - transparent standalone brand mark.
- `metadata/token-metadata.json` - Metaplex-compatible off-chain metadata.
- `metadata/token-list-entry.json` - Solana token-list style entry.
- `metadata/project-profile.json` - canonical project and link profile.
- `metadata/verification.json` - immutable token facts and authority proof.
- `submissions/trustwallet/...` - Trust Wallet submission-ready folder structure.

## Canonical public URLs after repository publication

- Metadata: https://raw.githubusercontent.com/triontoken/trion/main/metadata/token-metadata.json
- Primary logo: https://raw.githubusercontent.com/triontoken/trion/main/assets/logo.png
- 512 px logo: https://raw.githubusercontent.com/triontoken/trion/main/assets/logo-512.png

## Authority proof

Mint authority was permanently revoked on August 16, 2026.

Transaction:

`5HuRdkwBgnbxWzoLByGxVnYRT6CYnF9t2eoU8ZVNLkQceH2Vzj4nJwSWLWXj5Tkqy7jN5FNrEArD9Zw1mW1mo84h`

Proof: https://solscan.io/tx/5HuRdkwBgnbxWzoLByGxVnYRT6CYnF9t2eoU8ZVNLkQceH2Vzj4nJwSWLWXj5Tkqy7jN5FNrEArD9Zw1mW1mo84h

## Submission notes

This package prepares consistent public data for wallets and market-data services. Publication does not itself guarantee indexing, verification, price display, or acceptance by any third-party service. Each service may require a separate application, minimum activity, liquidity, security review, payment, or community verification.

Do not change the mint, decimals, supply, authority status, or official links in one file without updating every other file in this package.
