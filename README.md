# Mask Swap

**Private CEX-inspired swaps for the Cypher ecosystem.**

Standalone web app that works together with [Mask Wallet](https://github.com/Cypheranon-dev/Maskwallet).

## Features (v1)

- Swap between ETH, BTC, SOL, ZEC and Cypher (CYP)
- Private / shielded mode UI (powered by Cypher zk-STARK technology — demo)
- Seed Round participation (CYP $0.0025) with secure email routing
- Clean black + orange theme matching Cypher / Mask Wallet
- Live rate calculation, balance display, swap history
- Direct access via GitHub Pages + link from Mask Wallet

## Live Demo

After enabling GitHub Pages:  
`https://cypheranon-dev.github.io/Maskswap/`

## Seed Round Email Routing

1. Create a free form at [formspree.io](https://formspree.io).
2. Set the notification email to **cryptocapitalx8@gmail.com**.
3. Replace `YOUR_FORM_ID` in `index.html` with your form ID.
4. No secrets are stored in the repo.

## Security

See [SECURITY.md](SECURITY.md). No keys or sensitive data in client code.

## Integration with Mask Wallet

Mask Wallet has a button that opens this swap interface. Both apps share the Cypher privacy theme and can be used independently or together.

## Status

- Interactive demo ready
- Real private swaps require full Cypher protocol integration (next)
- Test version — do not use with real funds

## License

MIT
