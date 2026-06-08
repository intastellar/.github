# StellarMint

```text
  ____  _       _ _             __  __ _       _
 / ___|| |_ ___| | | __ _ _ __ |  \/  (_)_ __ | |_
 \___ \| __/ _ \ | |/ _` | '__|| |\/| | | '_ \| __|
  ___) | ||  __/ | | (_| | |   | |  | | | | | | |_
 |____/ \__\___|_|_|\__,_|_|   |_|  |_|_|_| |_|\__|
```

_The open-source RWA issuance studio for Stellar._

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](../LICENSE)
[![CI](https://img.shields.io/badge/CI-GitHub%20Actions-blue.svg)](../.github/workflows/ci.yml)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](docs/CONTRIBUTING.md)
[![Stellar](https://img.shields.io/badge/Stellar-testnet%20%2B%20mainnet-7D00FF.svg)](https://stellar.org)
[![CI](https://github.com/intastellar/stellarmint/actions/workflows/ci.yml/badge.svg)](https://github.com/intastellar/stellarmint/actions/workflows/ci.yml)

## What Is StellarMint?

StellarMint is an open-source, no-code/low-code studio for issuing real-world asset tokens on the Stellar blockchain. It helps teams model an asset, configure compliance controls, generate Stellar metadata, manage holders, and prepare distribution workflows without building every issuer tool from scratch.

RWA infrastructure is still hard to access in many emerging markets, especially across Africa. StellarMint focuses on practical issuance flows for real estate, bonds, commodities, carbon credits, funds, and equity-like instruments where teams need transparent asset records, wallet-based ownership, and compliance-aware transfer controls.

Stellar is a strong fit because it supports native asset issuance at the protocol level. You do not need a smart contract just to create a token, and issuer accounts can enable Authorization Required, Authorization Revocable, and Clawback Enabled flags for regulated holder workflows. When programmable behavior is needed, StellarMint connects to Soroban, Stellar's Rust-based smart contract platform.

## Supported Asset Classes

| Asset Class   | Description                                                                  | Typical use case                                       |
| ------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------ |
| Real Estate   | Fractional ownership or participation units tied to a property or portfolio. | Apartment blocks, commercial buildings, land projects. |
| Bond/Debt     | Fixed income instruments represented as transferable units.                  | Corporate notes, municipal debt, project finance.      |
| Commodity     | Tokens backed by physical or reserved commodities.                           | Gold, agricultural produce, warehouse receipts.        |
| Carbon Credit | Credits tied to verified emissions reduction or removal claims.              | Voluntary carbon markets, retirement workflows.        |
| Fund Share    | Units representing participation in a managed fund.                          | Private funds, investment clubs, treasury pools.       |
| Equity        | Equity-like ownership records subject to jurisdictional rules.               | Private company shares, cooperative membership units.  |
