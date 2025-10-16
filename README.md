# MegaETH Insights (Beginner Notes)

Short, non-technical notes while I learn how MegaETH achieves “real-time” behavior.

## 1) What makes MegaETH different (my words)
- Focus on end-to-end EVM performance to push latency down and throughput up.
- Designed to keep Ethereum compatibility (JSON-RPC) while adding a realtime layer for apps that need speed.

## 2) Concepts I’m reading about
- **Architecture**: overview + performance tricks across the stack.
- **Realtime API**: JSON-RPC compatible, but apps can tap into a realtime stream to exploit very short block times.
- **Mini vs EVM Blocks**: two block types; app design needs to know how/when to rely on each.

Sources: Official docs “Next Steps” entries (Architecture, Realtime API, Mini vs. EVM Blocks).  
I’ll expand these sections as I read and test things:
- https://docs.megaeth.com/

## 3) Testnet observations (to fill as I test)
- Added the testnet, claimed faucet, basic tx sent.
- Tracking latency/feel from a user perspective (subjective notes).
Ref: https://testnet.megaeth.com/

## 4) Token sale context (why I’m documenting)
- Registration window and mechanics are public; filling GitHub & social profiles can matter if oversubscribed.
- I keep everything transparent so the team can see authentic interest.
Refs:
- https://token.megaeth.com/
