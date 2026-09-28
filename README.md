# Solidity storage exercise

A small learning exercise using the Hardhat starter project. The custom contract stores one unsigned integer and exposes methods to update and read it.

## Read the exercise

- [`contracts/MyContract.sol`](contracts/MyContract.sol): `value`, `setValue` and `getValue`.
- [`scripts/deploy.js`](scripts/deploy.js): deploys `MyContract` using Hardhat and ethers.
- [`contracts/Lock.sol`](contracts/Lock.sol) and [`test/Lock.js`](test/Lock.js): the separate Hardhat starter example and its tests.

The `Lock` tests do not cover `MyContract`. This repository is a basic learning example, not an audited contract or a production application. Any caller can update `value`; access control is outside the scope of this exercise.

For my current work with Python, SQL and data quality, see **[Retail Catalogue Guard](https://github.com/Home-ad/retail-catalogue-guard)**.
