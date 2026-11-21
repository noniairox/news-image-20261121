# The World Today — 21 November 2026 front page

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/noniairox/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/noniairox/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

A one-page newspaper front page summing up Saturday, 21 November 2026.

Lead story: Russia launches its biggest attacks of the year on Ukraine —
more than 400 drones and 110 missiles overnight, at least eight killed in
Kyiv — and two Russian missiles and a suspected drone come down in Poland.
Prime Minister Tusk calls it a deliberate provocation; no injuries or
damage are reported in Poland.

Also on the page: the AI stock rout (Nasdaq down 5% on Friday, wiping out
all its 2026 gains; S&P 500 and Dow in correction; about $4tn lost in a
week), Trump defending his ties to Putin and Xi after the first three-way
US-China-Russia meeting in Shenzhen, and a round-up of the ICJ Myanmar
ruling reactions, the Houthi missiles over Riyadh, the UK-EU deal, and a
pancreatic-cancer pill trial.

## How it runs

`main.py` is pure standard library: it copies `entry.png` (1024x1024,
drawn beforehand with a local render script) into `MAKEFUN_OUTPUT_DIR`
(default `/output`). No third-party packages, no network, deterministic —
both runs write the same bytes.

## Sources

- Lead: Russia's biggest strikes of the year on Ukraine; missiles land in
  Poland; PM Tusk calls it a deliberate provocation.
- Markets: Nasdaq -5% on Friday, S&P 500 and Dow in correction, ~$4tn
  lost this week; Anthropic falls after its +17% IPO debut.
- Diplomacy: Trump defends ties to Putin and Xi after the Shenzhen
  three-way meeting; Zelensky calls Putin a "killer".
- Also: ICJ Myanmar genocide ruling reactions; Houthi missiles intercepted
  over Riyadh; UK-EU deal; pancreatic-cancer pill trial.

Design: the page is drawn and typeset locally with a hand-built 5x7
bitmap font (masthead, three stories, a night scene over Kyiv, a Nasdaq
chart, three flags, and an also-in-the-news strip). The dateline is
Saturday, 21 November 2026.
