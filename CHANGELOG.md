
## Version 0.1.3

### New Features

- Split up auction in lots of 100 xUSD instead of 100 STX

### Bug Fixes

- Fix auctioning off multiple collateral types

## Version 0.1.2

### New Features

- Calculate stability fees weekly and show them in UI
- Pay back stability fees

## Version 0.1.1

### Bug fixes

- Fix minting extra debt (xUSD) based on the correct collateral type

## Version 0.1.0

### New features

- Authenticate with Arkadiko through Stacks Web Wallet extension
- Add 3 collateral types: STX-A, STX-B and DIKO
- Add SIP10 reserve to allow creation of vaults with multiple collateral types
- Mint extra xUSD to use excess collateral
- Deposit extra collateral to protect a risky vault
- Withdraw extra collateral when collateralization ratio is healthy
- Pay back all debt in vault

### Minor Changes

- Upgraded and refactored `@stacks/connect` and `@stacks/connect-react` usage

### Bug fixes

- Fix manage vault pages to load correct data