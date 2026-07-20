# Hi, I'm GalacticChill

I'm a self-taught programmer using **Python** to explore where **data, machine
learning, and finance** meet. I learn best by building, so I set myself a simple
rule: ship one real, working project every week — no filler, no tutorials copied
out of a book. Just things I actually made and can explain.

## What I'm building

It all lives in **[weekly-builds](https://github.com/GalacticChill/weekly-builds)**,
a running log of that weekly habit. Each project is small but complete: clean
code, a proper README, charts, and a test suite that runs offline. The thread
tying them together is quantitative finance — turning raw market data into
decisions I can actually reason about.

The projects deliberately build on each other:

- **[Stock Toolkit](https://github.com/GalacticChill/weekly-builds/tree/main/projects/stock-toolkit)**
  — where it started: pull a stock's price history and measure its return,
  volatility, and worst drawdown.
- **[Portfolio Lab](https://github.com/GalacticChill/weekly-builds/tree/main/projects/portfolio-lab)**
  — from one stock to a whole basket: correlation between assets and the
  mean-variance optimization behind the classic "efficient frontier," including
  the realistic no-shorting version.
- **[Backtester](https://github.com/GalacticChill/weekly-builds/tree/main/projects/backtester)**
  — from *what's optimal in theory* to *what actually happens*: simulate holding a
  portfolio through real history with rebalancing and trading costs, then test
  signal-driven strategies (momentum, inverse-volatility) with **no lookahead
  bias** — the mistake that makes most amateur backtests look better than they are.

Each week tends to fix or extend the one before it. I like turning a limitation I
noticed into next week's project.

## How I work

- **Real over flashy.** I'd rather ship something modest that runs and is tested
  than something impressive that only works in a screenshot.
- **Honest results.** A backtest is a hypothesis, not a promise. I try to report
  the costs and caveats, not just the good numbers.
- **Explain it simply.** If I can't describe what a project does in plain English,
  I don't understand it well enough yet.

## Tools I reach for

Python, NumPy, pandas, SciPy, and matplotlib — with pytest keeping it honest.

## What's next

I'm working toward machine-learning-driven models and an original project built
around a question I genuinely care about. The weekly log keeps going.
