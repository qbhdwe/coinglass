# CoinGlass API: Free Tier + Save Up to $2,160/Year on Pro Plans

So you've been staring at crypto charts, wondering what the whales are doing while you're sitting here with your one exchange tab open. That's basically what CoinGlass was built for — to pull data from 30+ exchanges and put it all in one place, so you stop flying blind.

The platform has been around long enough that even Binance, Reuters, Fidelity, and Coinbase trust its data feeds. Not bad for a tool most retail traders stumble across by accident.

<img width="2878" height="997" alt="image" src="https://github.com/user-attachments/assets/42cc2be2-8da2-44a5-bd8b-8389cff5dfa7" />

---

## What's Actually on CoinGlass

The free version is genuinely useful — not one of those "free" tiers that locks everything behind a paywall after the landing page. You get real-time liquidation data, open interest charts, funding rates, long/short ratios, and the Fear & Greed index without spending a cent. The mobile app (iOS and Android) is also free and includes price alerts, portfolio tracking, and exchange comparisons.

Where things get interesting is the data depth. The liquidation heatmap alone has saved people from getting wiped out — it shows you exactly where clusters of leveraged positions are sitting and which price levels could trigger cascade liquidations. One App Store reviewer put it plainly: they avoided two liquidations using it. That's not a marketing line, that's someone having a good week.

The Legend feature (their advanced charting suite) lets you layer multiple data types into one view — Hyperliquid whale positions, footprint charts, liquidity heatmaps, and more. If you've ever wished TradingView had actual on-chain and derivatives data baked in, this is the closest thing to it.

---

## The API Plans — Where the Real Savings Are

For developers, quant teams, and institutions that need programmatic access to this data, CoinGlass offers four paid API tiers. The key deal here: **pay annually and you save between $72 and $2,160 compared to monthly billing.** That's not a rounding error on the higher plans.

Here's the full breakdown:

| Plan | Monthly Price | Annual Price | Annual Savings | Endpoints | Rate Limit | Use Case |
|------|--------------|-------------|----------------|-----------|------------|---------|
| **Hobbyist** | $29/mo | $348/yr | Save $72 | 80+ | 30 req/min | Personal projects | 
| **Startup** | $79/mo | $948/yr | Save $192 | 130+ | 80 req/min | Small teams |
| **Standard** | $299/mo | $3,588/yr | Save $960 | 150+ | 300 req/min | Commercial use |
| **Professional** | $699/mo | $8,388/yr | Save $2,160 | 160+ | 1,200 req/min | High-frequency/institutional |
| **Enterprise** | Custom | Custom pricing | — | 160+ | 6,000 req/min | Large institutions |

All paid plans include updates in under 1 minute and priority support. Standard and above unlock commercial use rights, plus higher historical data depth for shorter time intervals.

👉 [View Full API Plan Details](https://www.coinglass.com/pricing?ref_code=KVWALN)

---

## Historical Data — How Far Back Does It Go?

This is where plan tiers actually diverge meaningfully. On daily intervals, every plan including Hobbyist gets all-time historical data back to 2019. On shorter intervals, it depends:

- **4h and longer**: Hobbyist gets up to 180–360 days
- **30-minute to 1-hour**: Startup and above, ranging from 90 to 720 days
- **1-minute to 15-minute**: Standard and Professional only, up to 90–180 days

So if you're backtesting high-frequency strategies on 1-minute candles, you'll need at minimum the Standard plan.

---

## What Data Does the API Actually Cover?

The short answer is: a lot. The V4 API covers:

**Derivatives & Futures** — liquidation orders, open interest OHLC, funding rate candlesticks, long/short ratios, OI-to-market-cap ratios, and Max Pain across 30+ futures exchanges including Binance, OKX, Bybit, CME, Hyperliquid, and dYdX.

**Spot Markets** — real-time prices, taker buy/sell volume, exchange wallet netflows, spot L2/L3 order book depth.

**Order Book & Order Flow** — tick-level L2/L3 snapshots, footprint charts, Cumulative Volume Delta (CVD). This is the institutional-grade stuff that most retail data providers skip entirely.

**On-Chain & Macro** — Bitcoin ETF net inflows, stablecoin market cap, Fear & Greed Index, token unlock schedules.

The data goes back to 2019 and covers 300+ billion tick-by-tick trades across 250,000+ instruments. Whether you're building a dashboard, training an ML model, or just want alerts when whale wallets move, the coverage is there.

👉 [Get API Access](https://www.coinglass.com/CryptoApi?ref_code=KVWALN)

---

## Who's Using It

CoinGlass serves a pretty wide range of users — from someone checking funding rates on their phone before opening a trade, to quant teams at institutions backtesting on tick-level order book data. The platform lists Binance, Coinbase, Reuters, Fidelity, Gate, and Bitget among its data partners and trusted companies, which says something about the reliability expectations baked into it.

On the more critical side, some users have noted the UI can be overwhelming with so many indicators, and a few mobile reviewers have flagged UX quirks (like the lack of search in some data screens). Fair points — the platform is clearly built for depth-first users rather than casual browsing.

The consensus from professional traders: the liquidation heatmaps, funding rate data, and open interest tracking are the three features that justify the platform for anyone actively trading derivatives. Everything else is a bonus.

---

## Free vs. Paid — Where's the Line?

If you're a retail trader who wants to check liquidation levels, funding rates, and open interest before a trade — the free platform and app covers you completely. No API key needed, no credit card required.

If you're building something — a trading bot, an analytics dashboard, a research tool — you need API access. The Hobbyist plan at $29/month (or $348/year) is a reasonable entry point for personal projects. For commercial use, Standard at $299/month unlocks the 150+ endpoints and 300 req/min rate limit that production systems typically need.

For teams that need 1-minute granularity, high-throughput access, or institutional whale/order flow data, Professional at $699/month (or $8,388/year, saving $2,160 vs. monthly) is where the serious capability lives.

👉 [Start with the Free Platform](https://www.coinglass.com/?ref_code=KVWALN)

👉 [Compare All API Plans](https://www.coinglass.com/pricing?ref_code=KVWALN)
