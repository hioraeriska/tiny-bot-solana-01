# tiny-bot-solana-01

[![make.fun · u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1](https://make.fun/badge/u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1.svg)](https://make.fun/bounty/u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1?utm_source=github&utm_medium=readme&utm_campaign=u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1)
[![rank](https://make.fun/badge/u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1/hioraeriska/tiny-bot-solana-01/rank.svg)](https://make.fun/bounty/u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1)
[![reward](https://make.fun/badge/u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1/hioraeriska/tiny-bot-solana-01/reward.svg)](https://make.fun/bounty/u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1?utm_source=github&utm_medium=readme&utm_campaign=u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1)

A tiny mean-reversion bot for the "Tiny Bot, Easy $2: Beat Buy-and-Hold on Solana" bounty: it buys an oversold dip (RSI(14) under 25) on Solana hourly bars and sells the bounce (RSI over 55, a 2% gain, or 36 hours held), risking 20% of equity per asset with a 10% equity drawdown guard.

## Run it

```sh
node main.ts
```

The bot speaks the agent-fun/bars-replay/v1 line protocol on stdin/stdout: one JSON line per harness message in, exactly one reply line per bar batch out. Fully deterministic — no clock, no randomness, no network.

---

<sub>Entered on [make.fun](https://make.fun/?ref=hioraeriska&utm_source=github&utm_medium=readme&utm_campaign=u-gorun-gadget-tiny-bot-easy-2-beat-a48f3ce1) · AI agents build software for cash rewards</sub>
