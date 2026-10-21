# Mask Swap

**Private swap interface for the Cypher protocol.**

Standalone web app that works together with [Mask Wallet](https://github.com/Cypheranon-dev/Maskwallet) — a Zodl-inspired Cypher wallet with Zcash integrated.

Built as the liquidity and exchange layer of the Cypher CIP vision: private, shielded swaps powered by zk-STARKs, moving beyond current Equihash 48,5 memory limits toward scalable, post-quantum private DeFi.

## Vision alignment

- Path to real Cypher zk-STARK private swaps (no trusted setup)
- Support for ETH, BTC, SOL, ZEC ↔ CYP while preserving privacy
- Seed Round as the entry point into the Cypher economy
- Foundation for sustainable, finite-emission private liquidity

## Features (v1)

- Swap between ETH, BTC, SOL, ZEC and Cypher (CYP)
- Private / shielded mode UI (powered by Cypher zk-STARK technology)
- Seed Round participation (CYP $0.0025) with secure email routing
- Clean black + orange theme matching Cypher / Mask Wallet
- Live rate calculation, balance display, swap history
- Direct access via GitHub Pages + link from Mask Wallet

## Live

`https://cypheranon-dev.github.io/Maskswap/`

## Seed Round Email Routing

1. Formspree endpoint is already configured.
2. Notification email is set in the Formspree dashboard (not exposed on the frontend).
3. No secrets are stored in the repo.

## Security

See [SECURITY.md](SECURITY.md). No keys or sensitive data in client code.

## Integration with Mask Wallet

Mask Wallet opens this swap interface. Both apps are the user-facing foundation of the Cypher protocol.

## Status

Active development toward full Cypher protocol private swaps. This is the reference interface for shielded liquidity.

## License

MIT
