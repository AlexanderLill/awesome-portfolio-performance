# Awesome Portfolio Performance

This is an incomplete collection of repositories that add on top of [Portfolio Performance](https://github.com/buchen/portfolio), a simple tool to calculate the overall performance of an investment portfolio.

Note: I am not affiliated with Portfolio Performance, I just started this list. Feel free to create a PR to add to or edit this list!


# Importing Transaction Data

## Banking
- [krotata/mlp-to-portfolioperformance-converter](https://github.com/krotata/mlp-to-portfolioperformance-converter): Parses transactions from MLP https://mlp.de/, 🇩🇪 Germany, PDF to CSV)
- [runningman84/mpx2pp](https://github.com/runningman84/mpx2pp): Parses transactions from moneyplex (https://matrica.de/, 🇩🇪 Germany, CSV to CSV)
- [rlan/convert-csv-schwab2pp](https://github.com/rlan/convert-csv-schwab2pp): Parses transactions from Charles Schwab (https://www.schwab.com/, 🇺🇸 USA, CSV to CSV)

## Peer-to-Peer (P2P)
- [StegSchreck/PP-Auxmoney-Parser](https://github.com/StegSchreck/PP-Auxmoney-Parser): Parses transactions from P2P platform Auxmoney (https://www.auxmoney.com/, 🇩🇪 Germany, API to CSV)
- [ChrisRBe/PP-P2P-Parser](https://github.com/ChrisRBe/PP-P2P-Parser): Parses transactions from the P2P platforms Bondora (🇪🇪 Estland), Estateguru (🇪🇪 Estland), Lande (🇱🇻 Latvia), Mintos (🇱🇻 Latvia), Robocash (🇭🇷 Croatia), Swaper (🇪🇪 Estland), Debitum Network (🇱🇻 Latvia) and Viainvest (🇱🇻 Latvia) (CSV to CSV)
- [FireLars/pp-p2p-importer](https://github.com/FireLars/pp-p2p-importer): Parses transactions from the P2P platforms Bondora (🇪🇪 Estland), Fairr (?), Mintos (🇱🇻 Latvia), Viainvest (🇱🇻 Latvia)
- [StegSchreck/PP-Trine-Parser](https://github.com/StegSchreck/PP-Trine-Parser): Parses transactions from Trine (https://trine.com/, 🇸🇪 Sweden)

## Cryptocurrencies
- [pat-s/ppcryptoparser](https://github.com/pat-s/ppcryptoparser): Parses crypto staking rewards, supported coins: Cardano (ADA), Polkadot (DOT), Kusama (KSM), Solana (SOL) (to CSV)
- [AlexanderLill/PP-Crypto-Parser](https://github.com/AlexanderLill/PP-Crypto-Parser): Parses crypto transactions from Kraken and also supports importing staking rewards (https://www.kraken.com/, 🇺🇸 USA) 


# Importing Quotes
- [StevenReitsma/bnd-quotes](https://github.com/StevenReitsma/bnd-quotes): Quotes from Brand New Day (https://brandnewday.nl/, 🇳🇱 Nederlands)
- [fberg/ppserve](https://github.com/fberg/ppserve): Providing quotes from Ariva to Portfolio Performance (self-hosted API) (https://www.ariva.de/, 🇩🇪 Germany)
- [StegSchreck/HistoricMarketPriceDownloader](https://github.com/StegSchreck/HistoricMarketPriceDownloader): Downloads quotes from Ariva and provides them for import into Portfolio Performance as CSV (https://www.ariva.de/, 🇩🇪 Germany)
- [stasee/alphavantage_pp](https://github.com/stasee/alphavantage_pp): Providing quotes from Alphavantage to Portfolio Performance (self-hosted API) (https://www.alphavantage.co/, 🇺🇸 USA)


# Adding Additional Data
- [fbuchinger/etf-classification-pp](https://github.com/fbuchinger/etf-classification-pp): Classifies ETFs by currencies, countries, and industry sectors and determines TOP 10 holdings (only for iShares ETFs)
- [traits/pp_classification](https://github.com/traits/pp_classification): Classifies ETFs (GICS and ICB)


# Miscellaneous
- [rounakdatta/pp4z](https://github.com/rounakdatta/pp4z): PortfolioPerformance importer for Zerodha Console (https://console.zerodha.com/, 🇮🇳 India)
- [bschramke/ppxml](https://github.com/bschramke/ppxml): Java library to read Portfolio Performance XML files
- [Fabioni/PortfoliePerformance-Historische_Kurse_Tabelle_auf_einer_Webseite](https://github.com/Fabioni/PortfoliePerformance-Historische_Kurse_Tabelle_auf_einer_Webseite): Generates a link for querying OnVista for quotes (https://www.onvista.de/, 🇩🇪 Germany)
