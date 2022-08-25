# Nest Web Socket Stock Market

Proof-of-concept Nest.js web socket server for a simulated stock market

<details>
<summary>Table of Contents</summary>

- [Install](#install)
- [Build](#build)
- [Run the App](#run-the-app)
- [Client](#client)
- [Testing](#testing)
- [Environment](#environment)
- [Further Help](#further-help)
- [License](#license)

</details>

![demo](https://github.com/jseashell/nest-ws-stock-market/blob/main/demo.gif)

## Install

```
git clone git@github.com:jseashell/nest-ws-stock-market.git
cd nest-ws-stock-market
npm install
```

## Run the App

```sh
# Start a local dev server
npm start

# watch mode
npm run start:dev

# production mode
npm run start:prod
```

## Client

Check out the example [web client](https://www.github.com/jseashell/ng-ws-stock-market)!

...Or keep it simple with [example-client.html](./example-client.html). Run the server, then open the local file in a browser.

## Testing

```sh
# Unit tests
npm run test

# Coverage
npm run test:cov
```

## Environment

This app can be configured with a `.env` at the root of the project. Refer to the [.env.example](/.env.example) for options.

## Further help

- [NestJS](https://docs.nestjs.com/)
- [Socket.io](https://socket.io/)

## License

This software is distributed under the terms of the [MIT License](/LICENSE).
