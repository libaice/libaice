# Hi, I'm Bruce 👋

## Building on Prediction Market Infrastructure
focused on order lifecycle issues: ghost fills, stale signatures, cancel race conditions, and backtest/prod execution divergence.

## What I'm shipping
> [GhostGuard](https://github.com/orderbooktrade/ghostguard) 

Real-time ghost fill & stale signature detection for Polymarket market makers 

Verifies every CLOB fill against on-chain OrderFilled events. Webhook-based, language-agnostic.

> [rs-builder-relayer-client](https://github.com/orderbooktrade/rs-builder-relayer-client) 

Rust SDK for Polymarket's Builder Relayer (gasless tx relay, proxy vs EOA redemption paths).

> [OrderbookAgent](https://www.orderbook.trade/) 

AI pricing network for prediction markets (in development 💪).

> [Maker Rebate Reward Tracker](https://polymarket-maker-rebate-tracker.orderbook.trade/) 

Track maker wallet rewards

## Background
Building on-chain system across EVM, Solana, and Move chains.

Deep work on Polymarket internals: Builder Relayer architecture, CTF V1 → V2 migration, EIP-1271 signature validation, WS subscription field-presence format, feeRateBps / order payload structure, proxy vs EOA redemption.


## Stack
Go · Solidity · Rust · Move · TypeScript
If you're running a Polymarket MM bot and seeing any of:

> * Cancel requests returning 200 but orders still filling
> Backtest / production divergence
> order can't be found — already canceled or matched but size_matched = 0
> WS cancellation events not arriving
> Unexplained "mystery fills" eating PnL

I've been tracking engine-side regression across ~15 maker wallets and have p99 latency data + stale-signature event counts. Happy to compare notes.
Reach out

X/Telegram: [t.me/Iambaice](https://t.me/Iambaice) [x.com/Iambaice](https://x.com/Iambaice)