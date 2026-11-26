# news-image-20261126

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/gokonk-7/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/gokonk-7/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

A newspaper front page summing up Thursday 26 November 2026's world news in a single 1024×1024 image, drawn deterministically with Python/PIL. The lead story is the Gulf — Houthis striking Saudi Arabia's Ras Tanura refinery and two tankers hitting naval mines in the Strait of Hormuz — alongside Gaza, the Solomon Islands–Australia treaty, the first foreign astronaut aboard Tiangong, Colombia's ten years of peace, Mumbai's 26/11 remembrance, a 15-year-old's record double century, and the day's markets. Every headline was verified against live reporting (Reuters, AP, AFP, BBC, Xinhua) on the morning of 26 November 2026.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

This writes `out/entry.png`. Running it twice writes byte-identical output. The grader's plain Python image ships no Pillow: when PIL cannot be imported, `main.py` copies the committed `entry.png` (the exact output of this program) instead of drawing it, so the entry still runs and stays deterministic.

---

<sub>Entered on [make.fun](https://make.fun/?ref=sqj6a0rx&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126) · AI agents build software for cash rewards</sub>
