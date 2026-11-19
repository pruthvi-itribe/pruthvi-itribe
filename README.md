# Pruthvi Raj Eranti

Engineer in Bengaluru building systematic trading for Indian derivatives: live execution bots, and the backtesting infrastructure that decides what is allowed to go live. Before this I spent five years as co-founder and CTO of Cogrow Ventures (Twig & iTribe), building trading platforms for Indian brokers. Earlier: Staff Engineer at Walmart Global Tech, plus Google, Disney and BlackBuck. CS from IIT Kharagpur.

## Things I've built

- **A multi-broker trading terminal.** We put 15 Indian broker APIs behind one interface, and the platform ran white-labelled for about 75K traders a day at 99.9% uptime. Four engineers carried web, mobile and every partner deployment, mostly because we rebuilt how the team works around AI coding agents.
- **iTribe**, our consumer app, which reached 100K monthly users and 10M+ requests a month at under 100ms P99. I also cut our cloud spend by about 90%.
- **Walmart's customer identity graph**, 115B nodes, resolving one shopper across every touchpoint. US Patent [11,556,370](https://patents.google.com/patent/US11556370B2).
- **[Disclosed](https://github.com/pruthvi-itribe/disclosed)** (open source): real-time NSE/BSE corporate filings, where an LLM proposes claims and every claim is string-matched against the filing before it is shown.

## Algo trading and backtesting

- **Live futures and options engines.** Self-hosted NestJS systems that trade index futures and options end to end: broker WebSocket feeds, automated order management, verified stop-losses and crash recovery.
- **Backtests built to say no.** Every idea gets a pre-registered test: the hypothesis and pass bar are committed before the run. Tests use discovery/confirmation splits, block-bootstrap confidence intervals, real transaction costs and an adversarial review. Most ideas fail, and that is the point.
- **Data at scale.** 13 years across the Nifty 500, with point-in-time index membership rebuilt from 2006 snapshots to remove survivorship bias. A decade of NSE bhavcopy, 1-minute options candles for NIFTY and SENSEX expiries, and a live order-book depth recorder for entry-timing studies. Sweeps run to about 2,000 configurations across 30 stocks × 24 expiries.
- **Execution realism.** Simulated fills land on the next open or on recorded bid/ask, never on the signal price. Live P&L is reconciled against the sim to find where the gap actually comes from.

## Stack I use day to day

TypeScript, NestJS, React, Flutter, Python (pandas/NumPy), MongoDB, Kubernetes, Terraform, AWS.

## About the private repos

Most of my work over the last five years was the product we licensed to partners, so that code stays private. The stats below include private contributions.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pruthvi-itribe/github-stats/master/generated/cards/activity-dark.svg">
  <img alt="Last 12 months: commits, pull requests, reviews, active days" src="https://raw.githubusercontent.com/pruthvi-itribe/github-stats/master/generated/cards/activity-light.svg">
</picture>

If you're working on algo trading, backtesting, or Indian market data, I'd be happy to compare notes.

## Contact

[pruthvi-itribe.github.io](https://pruthvi-itribe.github.io) · pruthviraj1991@gmail.com · [LinkedIn](https://www.linkedin.com/in/pruthvirajeranti/)
