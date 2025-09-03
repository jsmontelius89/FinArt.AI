# Taxonomies

List of taxonomies:

- [Datasets taxonomy](#datasets-taxonomy)
  - [Overview](#overview)
  - [Fundamental data](#fundamental-data)
  - [Market data](#market-data)
  - [On-chain data (blockchain derived)](#on-chain-data-blockchain-derived)
  - [Financial sentiment data](#financial-sentiment-data)
  - [Macroeconomic \& network context](#macroeconomic--network-context)
  - [Alternative \& supplementary data](#alternative--supplementary-data)
- [Technical indicators taxonomy](#technical-indicators-taxonomy)


## Datasets taxonomy

### Overview

1. **Fundamental Data**
    - Valuation metrics
    - Supply & Tokenomics
    - Governance & Stability
    - Project Metadata
    - Competitor & Market Positioning
2. **Market Data**
    - Market Microstructure
    - Price and Volume Data
    - Derivatives Markets
    - Exchange Activity Data
3. **On-Chain Data (Blockchain Derived)**
4. **Financial Sentiment Data**
5. **Macroeconomic & Network Context**
    - Macroeconomic Indicators
    - Blockchain Network Metrics
    - Market Pressure Indicators
6. **Alternative & Supplementary Data**


### Fundamental data

| Indicator/Metric                             | Group                   | Data Level | Frequency of changes    | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|-------------------|---------------------|
| Market cap                                  | Valuation metrics       | Derived    | Medium  | -                   |
| Fully diluted valuation                     | Valuation metrics       | Derived    | Medium  | -                   |
| Total supply                                | Supply & tokenomics     | Raw        | Low     | +                   |
| Circulating supply                          | Supply & tokenomics     | Raw        | Medium  | +                   |
| Max supply                                  | Supply & tokenomics     | Raw        | Low     | +                   |
| Inflation rate (token inflation rate)      | Supply & tokenomics     | Derived    | Medium  | +                   |
| Token issue schedule / future token issuance | Supply & tokenomics   | Derived    | Low     | +                   |
| Token lockup / vesting schedules            | Supply & tokenomics     | Raw        | Low     | +                   |
| Token burning data                          | Supply & tokenomics     | Raw        | Medium  | +                   |
| Governance model (on-chain, off-chain, hybrid) | Governance & stability | Raw        | Low     | +                   |
| Centralization metrics: team-managed token share, concentration of large holders | Governance & stability | Derived | Medium | +                   |
| Smart contract security audits: auditor, last audit date, audit findings, security score | Governance & stability | Raw | Low | +                   |
| Presence & distribution: number of chains deployed, CEX listings, bridge availability | Governance & stability | Raw | Medium | +                   |
| Documentation: whitepaper, litepaper, roadmap | Project metadata       | Raw        | Low     | +                   |
| Fundraising information: funding rounds, amounts, investors | Project metadata | Raw        | Low     | -                   |
| Team & advisors info (when available)       | Project metadata        | Raw        | Low     | -                   |
| Partnerships & ecosystem relations          | Project metadata        | Raw        | Low     | -                   |
| Competitors list                            | Competitor & market positioning | Raw  | Low     | -                   |
| Market share (by market cap, volume, user base) | Competitor & market positioning | Derived | Medium | -                   |
| Sector/category classification (defi, NFT, layer-1, etc.) | Competitor & market positioning | Raw | Low | + |


### Market data

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Order book data: bids, asks, depth          | Market microstructure   | Raw        | High   | -                   |
| Trade ticks / transaction-level trades      | Market microstructure   | Raw        | High   | -                   |
| Liquidity metrics: spread, turnover, depth, slippage | Market microstructure | Derived  | High   | -                   |
| OHLCV: aggregated price/volume multiple intervals (e.g., 2s, 1m, 1h, 1d) | Price and volume data | Raw        | Medium- to high | -                   |
| Volatility measures: realized, implied, historical | Price and volume data | Derived    | Medium | -                   |
| VWAP (volume weighted average price)        | Price and volume data   | Derived    | Medium | -                   |
| Derivatives data: futures and options open interest, volume, prices | Price and volume data | Raw        | Medium | -                   |
| Open interest                               | Derivatives markets     | Raw        | Medium | -                   |
| Volume                                      | Derivatives markets     | Raw        | Medium | -                   |
| Prices (futures, options)                    | Derivatives markets     | Raw        | Medium | -                   |
| Funding rates (perpetual swaps)             | Derivatives markets     | Derived    | High   | -                   |
| Implied volatility surfaces (options)       | Derivatives markets     | Derived    | Medium | -                   |
| Deposits & withdrawals flows on CEXs and bridges | Exchange activity data | Raw        | Medium | +                   |
| Exchange order books (aggregate snapshots)  | Exchange activity data  | Raw        | Medium | -                   |
| Exchange market share & liquidity distribution | Exchange activity data | Derived    | Medium | -                   |

### On-chain data (blockchain derived)

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Transaction counts and volumes               | On-chain data           | Raw        | Medium | +                   |
| Active addresses (daily/monthly active)      | On-chain data           | Raw        | Medium | +                   |
| Holder distribution (e.g., by wallet size buckets) | On-chain data         | Derived    | Medium | +                   |
| Whales activity (large transactions, accumulations, dumps) | On-chain data       | Derived    | Medium | +                   |
| Insider activity (founders, team transfers) | On-chain data           | Derived    | Medium | +                   |
| Token transfers and contract interactions   | On-chain data           | Raw        | Medium | +                   |
| Smart contract events logs                   | On-chain data           | Raw        | Medium | +                   |


### Financial sentiment data

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Social media mentions: volume and sentiment scores | Financial sentiment data | Derived | High   | -                   |
| News sentiment: automated hack, regulation, partnership news detection | Financial sentiment data | Derived | Medium | -                   |
| Community sentiment: discord, twitter, reddit, bitcointalk | Financial sentiment data | Derived | Medium | -                   |
| Influencer analytics: top voices impact measurement | Financial sentiment data | Derived | Medium | -                   |
| Sentiment event correlations to price/volatility | Financial sentiment data | Derived | Medium | -                   |


### Macroeconomic & network context

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Global economic indicators (GDP, inflation, treasury yields) | Macroeconomic indicators | Raw/Derived | Low    | -                   |
| Energy prices (electricity, gas) relevant for mining costs | Macroeconomic indicators | Raw        | Medium | -                   |
| Cryptocurrency market dominance (BTC dominance, ETH dominance) | Macroeconomic indicators | Derived    | Medium | +                   |
| Regulatory environment updates & indices    | Macroeconomic indicators | Raw        | Low    | -                   |
| Mining data: hash rate, difficulty, block times | Blockchain network metrics | Raw      | High   | +                   |
| Network performance: block size, fee metrics, mempool size | Blockchain network metrics | Raw/Derived | High  | +                   |
| Chain health metrics (fork rate, orphan blocks) | Blockchain network metrics  | Derived   | Medium | +                   |
| BTC / ETH holdings in public companies/institutions | Market pressure indicators | Derived    | Medium | +                   |
| ETF flows: inflows, outflows, balance changes | Market pressure indicators | Derived    | Medium | -                   |
| Stablecoin supply & flows                    | Market pressure indicators | Raw/Derived | Medium | +                   |
| Institutional wallet activity                | Market pressure indicators | Derived    | Medium | +                   |


### Alternative & supplementary data

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Developer activity: GitHub commits, PRs, issues, contributor metrics | Alternative & supplementary data | Raw/Derived | Medium | +                   |
| Search & trend data: Google trends, Twitter trends | Alternative & supplementary data | Derived    | Medium | -                   |
| Protocol usage metrics: TVL (total value locked), active users in defi protocols | Alternative & supplementary data | Derived | Medium | +                   |

## Technical indicators taxonomy

- **Trend-Following Indicators**
  - *Moving Averages (SMA, EMA, WMA):* Averages prices over time to signal trend direction; EMA weights recent prices more. [Investopedia](https://www.investopedia.com/terms/m/movingaverage.asp)
  - *Parabolic SAR:* Indicates potential trend reversals with stop and reverse points based on price and time. [Investopedia](https://www.investopedia.com/terms/p/parabolicindicator.asp)
  - *Average Directional Index (ADX):* Measures trend strength regardless of direction. [Investopedia](https://www.investopedia.com/terms/a/adx.asp)
  - *Moving Average Convergence Divergence (MACD):* Combines moving averages to show trend direction and momentum. [Investopedia](https://www.investopedia.com/terms/m/macd.asp)

- **Momentum Indicators**
  - *Relative Strength Index (RSI):* Quantifies overbought or oversold conditions on a 0-100 scale. [Investopedia](https://www.investopedia.com/terms/r/rsi.asp)
  - *Stochastic Oscillator:* Compares closing price to price range over a period to indicate momentum. [Investopedia](https://www.investopedia.com/terms/s/stochasticoscillator.asp)
  - *Rate of Change (ROC):* Measures percentage price change over a time period. [Investopedia](https://www.investopedia.com/terms/r/roc.asp)
  - *MACD:* Used also as a momentum oscillator showing the relationship between two moving averages.

- **Volume Indicators**
  - *On-Balance Volume (OBV):* Cumulative volume adding or subtracting based on price movement direction. [Investopedia](https://www.investopedia.com/terms/o/onbalancevolume.asp)
  - *Chaikin Money Flow (CMF):* Combines price and volume to show buying/selling pressure. [Investopedia](https://www.investopedia.com/terms/c/chaikinmoneyflow.asp)
  - *Volume Rate of Change:* Percentage change in volume across a defined period. [Fidelity PDF](https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/learning-center/Understanding-Indicators-TA.pdf)
  - *Money Flow Index (MFI):* Volume-weighted RSI indicating money inflow or outflow. [Investopedia](https://www.investopedia.com/terms/m/mfi.asp)

- **Volatility Indicators**
  - *Bollinger Bands:* Bands set at standard deviations above/below a moving average to signal volatility. [Investopedia](https://www.investopedia.com/terms/b/bollingerbands.asp)
  - *Average True Range (ATR):* Measures average price range over time to indicate volatility. [Investopedia](https://www.investopedia.com/terms/a/atr.asp)
  - *Keltner Channels:* Volatility-based envelopes above and below an exponential moving average. [Investopedia](https://www.investopedia.com/terms/k/keltnerchannels.asp)
  - *Donchian Channels:* High and low price boundaries over a period used to detect breakouts. [Investopedia](https://www.investopedia.com/terms/d/donchianchannels.asp)

- **Breadth Indicators**
  - *Advance-Decline Line:* Cumulative difference between advancing and declining stocks in a market/index. [Investopedia](https://www.investopedia.com/terms/a/advancedeclineline.asp)
  - *McClellan Oscillator:* Measures momentum of advance-decline data to gauge market breadth. [Investopedia](https://www.investopedia.com/terms/m/mcclellanoscillator.asp)
