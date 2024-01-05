# React Cryptocurrency App
Built on React, this cryptocurrency app leverages RESTful calls from the CoinGecko API, specifically utilizing v3 for real-time data retrieval (as of the project's initiation). The user interface is designed with Ant Design, ensuring a sleek and intuitive user experience. Stay updated with the latest cryptocurrency information seamlessly, thanks to the efficient integration of CoinGecko API and the modern UI provided by Ant Design.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Project Deployed Link
https://divyamehndhiratta.github.io/crypto-app/#/ 

# Project Structure 
Generated with `tree` command.
```
.
├── API
│   └── index.js
├── ChartConfig
│   └── index.js
├── components
│   ├── App.css
│   ├── App.js
│   ├── Coins
│   │   ├── ReactCoinCommunityStats.js
│   │   ├── ReactCoinDetailSummary.js
│   │   ├── ReactCoinDeveloperStats.js
│   │   ├── ReactCoinMarketDetailedStats.js
│   │   ├── ReactCoinMarketStats.js
│   │   ├── ReactCoinScores.js
│   │   ├── ReactCoinsDetail.js
│   │   └── ReactCoinsList.js
│   ├── Empty
│   │   └── ReactEmpty.js
│   ├── Events
│   │   └── ReactEvents.js
│   ├── ExchangeRates
│   │   └── ReactExchangeRates.js
│   ├── Exchanges
│   │   └── ReactExchangesList.js
│   ├── General
│   │   ├── ReactAbout.js
│   │   └── ReactHome.js
│   ├── Global
│   │   └── ReactGlobal.js
│   ├── Navigation
│   │   ├── ReactFooter.js
│   │   ├── ReactHeader.js
│   │   └── ReactSider.js
│   └── StatusUpdates
│       └── ReactStatusUpdates.js
├── constants
│   └── index.js
├── images
│   ├── branding
│   │   └── CoinGecko.png
│   ├── flaticon
│   │   ├── 001-bitcoin.svg
│   │   ├── 001-chat.svg
│   │   ├── 002-bitcoin-1.svg
│   │   ├── 002-bitcoin.svg
│   │   ├── 003-bitcoin-2.svg
│   │   ├── 003-smartphone.svg
│   │   ├── 004-exchange.svg
│   │   ├── 005-idea.svg
│   │   ├── 006-binary.svg
│   │   └── worldwide.svg
│   └── logo
│       └── logo.png
├── index.js
├── redux_actions
│   └── index.js
├── redux_reducers
│   └── index.js
└── styles
    └── index.js
```

# Themes
The themes for this app will directly correlate to the api endpoints provided by the CoinGecko API. I want to split up the app into digestible React components in the following areas, which will most likely form part of a larger dashboard interface.

- Coins
- Exchanges
- Status Updates
- Exchange Rates
- Events
- Global

# Requirements (npm)
Requirements for this project can be found in the package.json. And can be installed with `npm install` from root of the project directory.

I aim to use the following packages:
**must have packages**
- antd (ui framework for react)
- react (front-end)
- react-router-dom (routing for react)
- chartjs (charting library)
- axios (graceful api calls)

**optional packages**
- redux (may need redux for state management if number of components grows)
- ant motion (animations for ant design ui)


# Tests

# Sources
- [The CoinGecko API](https://www.coingecko.com/en/api#)
- [React documentation](https://reactjs.org/docs/getting-started.html)
- [Ant Design Documentation](https://ant.design/docs/react/introduce)

# Steps to reproduce

```sh
# install dependencies and start local server (make sure you have nvm and yarn installed beforehand)
nvm use
yarn
yarn start

# building
yarn build
```
