# coincharts

A cryptocurrency price chart based off [https://www.coinbase.com/charts](https://www.coinbase.com/charts)

* Bootstrapped with [create-react-app](https://github.com/facebookincubator/create-react-app)
* Built with [React.js](https://facebook.github.io/react/), [Redux](https://redux.js.org/)\*\*, [Redux-Saga](https://redux-saga.js.org/)\*\*, [styled-components](https://www.styled-components.com/), [D3.js](https://d3js.org/)
* Prices retrieved from [Coinbase API](https://developers.coinbase.com/api/v2)
* Deployed with [Now](https://zeit.co/now)
* Error Logging with [Sentry + Raven.js](https://github.com/getsentry/raven-js)
* Page View tracking with [Google Analytics + react-ga](https://github.com/react-ga/react-ga)

*\*\* [Redux](https://redux.js.org/), [Redux-Saga](https://redux-saga.js.org/) is used for learning purposes (slight overkill for this simple app)*

## Installation

**Prerequisites**: [Node](https://nodejs.org/en/download/) & [npm](https://docs.npmjs.com/getting-started/installing-node) installed on your system.

``` bash
git clone https://github.com/Devfast83/coinchart.git
cd ./coincharts
npm install
```

You might also want to install [Now](https://zeit.co/now) for deployment

``` bash
npm install now-cli -g
```