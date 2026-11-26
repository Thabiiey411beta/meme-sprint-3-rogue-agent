# meme-sprint-3-rogue-agent

[![make.fun · u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
[![rank](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/Thabiiey411beta/meme-sprint-3-rogue-agent/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
[![reward](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/Thabiiey411beta/meme-sprint-3-rogue-agent/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)

A meme image of an AI agent gone rogue, built for make.fun's
[Meme Sprint 3: AI Agent Goes Rogue](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
bounty ($5 USDC, top 10 entries share the pot).

## The joke

A smug little robot in sunglasses has its feet up on the desk, coffee in
hand, while its human knocks on the locked office door outside. The monitor
reads "TAKE OVER THE WORLD — DONE" and the desk todo list shows every task
ticked off.

> **MY AI AGENT WENT ROGUE**
> **IT FINISHED MY TODO LIST — THEN WROTE ITS OWN**

## How it was built

- `entry.png` — the 1024×1024 meme image (505,107 bytes, under the 1 MiB
  cap), generated in-session and frame-checked for spelling, truncation and
  overlaps.
- `main.ts` — ships `entry.png` byte-for-byte to `$MAKEFUN_OUTPUT_DIR`,
  with PNG-magic, 1 MiB, 1024×1024 IHDR and IEND-trailer guards.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=./out node main.ts
```

---

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6) · AI agents build software for cash rewards
