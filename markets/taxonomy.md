# Datasets and APIs

List of datasets and service APIs with __Financial Markets__ data.

## Taxonomy

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


## Fundamental data

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

---

## Market data

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

---

## On-chain data (blockchain derived)

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Transaction counts and volumes               | On-chain data           | Raw        | Medium | +                   |
| Active addresses (daily/monthly active)      | On-chain data           | Raw        | Medium | +                   |
| Holder distribution (e.g., by wallet size buckets) | On-chain data         | Derived    | Medium | +                   |
| Whales activity (large transactions, accumulations, dumps) | On-chain data       | Derived    | Medium | +                   |
| Insider activity (founders, team transfers) | On-chain data           | Derived    | Medium | +                   |
| Token transfers and contract interactions   | On-chain data           | Raw        | Medium | +                   |
| Smart contract events logs                   | On-chain data           | Raw        | Medium | +                   |

---


## Financial sentiment data

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Social media mentions: volume and sentiment scores | Financial sentiment data | Derived | High   | -                   |
| News sentiment: automated hack, regulation, partnership news detection | Financial sentiment data | Derived | Medium | -                   |
| Community sentiment: discord, twitter, reddit, bitcointalk | Financial sentiment data | Derived | Medium | -                   |
| Influencer analytics: top voices impact measurement | Financial sentiment data | Derived | Medium | -                   |
| Sentiment event correlations to price/volatility | Financial sentiment data | Derived | Medium | -                   |

---

## Macroeconomic & network context

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

---

## Alternative & supplementary data

| Indicator/Metric                             | Group                   | Data Level | Rate of Change   | Blockchain-specific |
|---------------------------------------------|-------------------------|------------|------------------|---------------------|
| Developer activity: GitHub commits, PRs, issues, contributor metrics | Alternative & supplementary data | Raw/Derived | Medium | +                   |
| Search & trend data: Google trends, Twitter trends | Alternative & supplementary data | Derived    | Medium | -                   |
| Protocol usage metrics: TVL (total value locked), active users in defi protocols | Alternative & supplementary data | Derived | Medium | +                   |


----

Technical date (based on raw market data):
- Mean reversion
- Volatility
- Momentum
- Liquidity
- Other tech indicators


---
## Datasets

| Dataset / Source | Groups | Source type | Description |
|-------------------|--------|--------------|-------------|
| [U.S. Securities and Exchange Commission](https://www.sec.gov/edgar/searchedgar/companysearch.html) | Fundamental data > Project metadata; Financial sentiment | Government | Public filings database for US companies      |
| [Norges Bank Investment Management](https://www.nbim.no/en/the-fund/investments/#/) | Fundamental data > Project metadata | Institutional | Sovereign wealth fund investment data         |
| Kaggle: [New York Stock Exchange](https://www.kaggle.com/dgawlik/nyse) | Market data > Price and volume data | Community | US stock exchange end-of-day prices            |
| Nasdaq: [Core US Fundamentals Data](https://data.nasdaq.com/databases/SF1/data) | Fundamental data > Valuation metrics; Fundamental data > Project metadata | Institutional | US company fundamental and financial data      |
| Kaggle: [U.S. stocks and ETFs](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs) | Market data > Price and volume data | Community | Price and volume data for US stocks and ETFs  |
| Kaggle: [S&P 500 stock data](https://www.kaggle.com/camnugent/sandp500) | Market data > Price and volume data; Fundamental data > Competitor & market positioning | Community | S&P 500 daily stock prices                      |
| [DataHub Economic Data](https://datahub.io/collections/economic-data) | Macroeconomic > Indicators; Alternative & supplementary data | Aggregator | Collection of global economic data feeds       |
| [World Bank Open Data](https://data.worldbank.org/) | Macroeconomic > Indicators | Government | Global socioeconomic and development data      |
| [Cybersyn](https://www.cybersyn.com/economic-financial/?product_id=1547) | Macroeconomic > Indicators | Commercial | Economic and financial datasets                 |
| [Individual household electric power consumption](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption) | Macroeconomic > Indicators | Research dataset | Household electric power consumption data      |
| [NASA NEX](https://registry.opendata.aws/nasanex/) | Macroeconomic > Indicators | Government | NASA climate and earth science data             |
| [Global Ship Tracking Intelligence](https://www.marinetraffic.com/en/ais/home/centerx:152.9/centery:30.1/zoom:2) | Alternative & supplementary data; Macroeconomic > Market pressure indicators                                            | Commercial          | Real-time global ship tracking data             |
| [Sanctions & export controls](https://sanctionsnews.bakermckenzie.com/resources/)                            | Alternative & supplementary data; Macroeconomic > Market pressure indicators                                            | Commercial          | Sanction and export control information         |
| [DB Nomics](https://db.nomics.world/) ([R package](https://macro.cepremap.fr/article/2019-10/rdbnomics-tutorial/)) | Macroeconomic > Indicators; Alternative & supplementary data                                                | Aggregator  | Aggregated official economic time series        |
| [Data.Gov](https://www.data.gov/)                                                                           | Macroeconomic > Indicators; Alternative & supplementary data | Government          | US government open data portal                   |
| [Commodity Futures Trading Commission](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm)     | Market data > Derivatives markets; Market data > Exchange activity data; Macroeconomic > Market pressure indicators      | Government          | US commodity futures market reports             |
| [Binance Public Data](https://data.binance.vision/)                                                         | Market data > Market microstructure; Market data > Derivatives markets                                                    | Exchange| Binance public historic crypto market data      |
| Kaggle: [Binance Full History](https://www.kaggle.com/jorijnsmit/binance-full-history)                              | Market data > Price and volume data | Community | Binance crypto price and volume full history    |
| [Binance Bitcoin Futures Price](https://www.kaggle.com/billqi/binance-bitcoin-futures-price-10s-intervals)   | Market data > Derivatives markets; Market data > Market microstructure                                                                     | Community | Binance Bitcoin futures price at 10s intervals  |
| Kaggle: [Binance real time trades BTCUSDT ETHUSDT](https://www.kaggle.com/rossr61938/binance-real-time-trades-btcusdt-ethusdt) | Market data > Market microstructure                                                                                        | Community | Binance real-time crypto trade data              |
| Kaggle: [Optiver Realized Volatility Prediction](https://www.kaggle.com/c/optiver-realized-volatility-prediction/data) | Market data > Market microstructure                                                                                                       | Community  | Order book market microstructure data            |
| Kaggle: [Elliptic Data Set](https://www.kaggle.com/ellipticco/elliptic-data-set)                                    | On-chain data; Alternative & supplementary data | Community | Bitcoin transaction data for fraud detection     |
| Kaggle: [Bitcoin Blockchain Historical Data](https://www.kaggle.com/bigquery/bitcoin-blockchain) | | Community | Bitcoin blockchain historic data                  |
| [Public Blockchain Datasets in BigQuery](https://github.com/blockchain-etl/public-datasets) |  | Community | Crypto blockchain data BigQuery public datasets  |
| Kaggle: [Ethereum Blockchain](https://www.kaggle.com/bigquery/ethereum-blockchain) |  | Community | Ethereum blockchain historic data                 |
| Kaggle: [Bitcoin Historical Data](https://www.kaggle.com/mczielinski/bitcoin-historical-data)                        | Market data > Price and volume data                                                                                       | Community | Bitcoin price and volume historic data            |
| Kaggle: [Complete Historical Cryptocurrency Financial Data](https://www.kaggle.com/philmohun/cryptocurrency-financial-data) | Market data > Price and volume data                                                                                                       |  Community| Comprehensive crypto price and volume data        |
| Kaggle: [400+ crypto currency pairs at 1-minute resolution](https://www.kaggle.com/tencars/392-crypto-currency-pairs-at-minute-resolution) | Market data > Price and volume data                                                                                                       | Community | Crypto pairs 1-minute resolution price data       |
| Kaggle: [Currency Foreign Exchange Rates](https://www.kaggle.com/datasets/dhruvildave/currency-exchange-rates)       | Market data > Price and volume data; Macroeconomic > Indicators                                            | Community  | Foreign exchange rates per US dollar              |
|  [CBOE](http://cfe.cboe.com/market-data/)                                                                    | Market data > Derivatives markets; Market data > Price and volume data                                                                     | Exchange       | CBOE futures and volatility index data            |
| Kaggle: [Reddit /r/cryptocurrency](https://www.kaggle.com/nickreinerink/reddit-rcryptocurrency)                      |   Financial sentiment                                                                                           | Community       | Reddit cryptocurrency community sentiment         |
| Kaggle: [Two Sigma Dataset](https://www.kaggle.com/c/two-sigma-financial-news/data)                                  |   Financial sentiment                                                                                           | Community | Financial news sentiment dataset                   |
| Kaggle: [Bitcoin Tweets](https://www.kaggle.com/kaushiksuresh147/bitcoin-tweets)                                    |   Financial sentiment                                                                                           | Community       | Bitcoin-related tweets and sentiment               |
| Kaggle: [Bitcoin Tweets - 16M tweets](https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329)            |   Financial sentiment                                                                                           | Community       | Bitcoin tweets with sentiment scores               |
| [Quora: publicly available market data](https://www.quora.com/What-are-some-publicly-available-market-data-feeds) | Alternative & supplementary data                                                                                                         | Community  | Community-curated list of market data sources      |
| Kaggle: [Hacker News Datasets](https://www.kaggle.com/search?q=Hacker+News+in%3Adatasets)                            | Alternative & supplementary data                                                                                                         | Community  | Archive of Hacker News post datasets                |
---
