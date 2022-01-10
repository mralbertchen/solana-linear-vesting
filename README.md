# Solana Linear Vesting

## Background

Token lockup and vesting is one of the most common ways for investors to receive their private round tokens. Since Ethereum days there have been a few implementations of this smart contract. A Linear Vesting program provides a simple mechanism that can release a token balance gradually like a typical vesting scheme, with a cliff and vesting period. Optionally revocable by the owner. A proper deployment of the program will ensure this beneficiary can never actually retrieve tokens before vesting. Funds are never in an SPL token wallet owned by a user, and are completely program controlled.
This repo has all the basic wirings for a take-home assignment.

## Build and Test

This program is built with the Anchor framework (https://github.com/project-serum/anchor) and assumes you have an Anchor environment set up with all its dependencies.

First, install the js packages:

```
$ yarn
```

Then you can run the tests:

```
$ anchor test
```

