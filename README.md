# Coinster CLI

Command line interface written in Node.js to check cryptocurrency prices

Register an API key at https://nomics.com

## Usage

```
npm install

npm link
```

## Commands

```
# Help & Commands
coinster -h

# Version
coinster -V

# API Key Commands
coinster key set
coinster key show
coinster key remove

# Crypto Check Commands
coinster check price

# Check Specific Coins (default: BTN,ETH,XRP)
coinster check --coin=BTC,ETH

# Choose Currency (Default: USD)
coinster check --cur=EUR
```

### Version

1.0.0

### License

MIT
