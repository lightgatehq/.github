<div align="center">

![Lightgate](./banner.svg)

**Blockchains made financial state public, but not understandable.**

Lightgate transforms raw onchain state into trusted financial context.

**[orionhq.run](https://orionhq.run)** · [Orion Docs](https://orionhq.run/docs/guides) · **[attestprotocol.org](https://attestprotocol.org)** · [Attest Docs](https://docs.attest.so)

</div>

## Why legibility

Financial systems don't lack rails. They lack legibility. Every balance, position, and claim already lives onchain, but as raw state it answers nothing: who is this counterparty, what do they hold, what has actually happened here? Lightgate is an independent product and research company building open infrastructure that turns that state into context you can build on. Two graphs, one thesis: trust and finance are the two things markets need to read clearly.

## Products

| Product | What it is |
|---------|------------|
| [Attest Protocol](https://attestprotocol.org) | The trust graph: identity, reputation, claims, and attestations onchain. [Docs](https://docs.attest.so) · [Sandbox](https://sandbox.attest.so) · [Explorer](https://stellar.attestprotocol.org) |
| [Orion](https://orionhq.run) | The financial graph: a DeFi positions and activity API, starting with Stellar. [Docs](https://orionhq.run/docs/guides) · [API Reference](https://orionhq.run/docs/api) |

One call against Orion returns complete DeFi positions for any Stellar address, pinned to an exact ledger:

```bash
curl https://query.orionhq.run/v1/users/G.../positions \
  -H "x-orion-api-key: $ORION_KEY"
```

Get a key and explore the full surface at [orionhq.run/docs/api](https://orionhq.run/docs/api). Repositories open up here as products mature.

## History

Lightgate grew out of Daccred (decentralized accreditation), which became Attest Protocol and expanded into the company you're looking at. Along the way: [Public Goods Award at the Solana Radar Hackathon](https://x.com/solana/status/1856362113561964676), and Stellar Community Fund award recipient for attestation infrastructure.

---

<div align="center">

**Make markets legible.**

[Attest](https://attestprotocol.org) · [Orion](https://orionhq.run)

</div>
