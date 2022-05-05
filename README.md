# smartcontract-lottery

## Summary

This project allows to create a blockchain lottery with ETH based on a USD fee. The admins will close the lottery when is over and the lottery will select a random winner. Contract contained:

- `Lottery`: It creates the lottery with all it's functions

- [smartcontract-lottery](#smartcontract-lottery)
  - [Summary](#summary)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
  - [Scripts](#scripts)
  - [Testing](#testing)
- [License](#license)

## Prerequisites

Please install or have installed the following:

- [nodejs and npm](https://nodejs.org/en/download/)
- [python](https://www.python.org/downloads/)
- [brownie](https://eth-brownie.readthedocs.io/en/stable/install.html)
- [ganache-cli](https://www.npmjs.com/package/ganache-cli)

# Usage

## Scripts

```bash
brownie run scripts/deploy_lottery.py
```

It will create, start, end the lottery selecting a winner

## Testing

```
brownie test
```

# License

This project is licensed under the [MIT license](LICENSE).
