## TypeScript NFT exercise

_A brief exercise to create an NFT-like object in TypeScript (or JavaScript)._

## Motivation

This exercise is designed to allow you to show in under an hour:

- you write readable, maintainable code
- you can implement a simply specified system
- you're comfortable with typed code (optional)

If you're new to Blockchain and NFTs, you might find it interesting!

## In a hurry

- Clone this repository
- Install the dependencies `npm install`[1]
- Create a new file `src/nft.ts`[2]
- Export a default function of type `NFTCreateFn`[3]
- Implement the interface & types from `src/supporting.ts`
- Run the tests to verify your solution `npm test`[4]
- Email your solution to careers@medallion.fm

## Introduction

At a basic level, the Ethereum NFT spec allows tracking ownership of
distinguishable assets. Each owner is represented by a string address, and each
asset by a unique integer.

To complete this exercise you'll create a TypeScript object (or class) which
keeps track of assets and their owners, implementing the following methods:

- `balanceOf` returns the number of assets held by an owner
- `ownerOf` returns the owner of a specific asset
- `transferFrom` transfers an asset from one owner to another

You'll also need a function which accepts a list of owners and balances
to initialise the assets (with sequential, zero-indexed, integer identifiers)
and returns the object.

**We'll check your submission against the provided test suite, following the
developer comments found in `src/supporting.ts`. However, we're looking for a
good approach to the problem, not a perfect solution.**

## Supporting files

While you only need to submit a single `.ts` (or `.js`) file, we're providing
these to (hopefully) help make development easier:

- `src/supporting.ts` predefined types and interfaces
- `src/nft.spec.ts` a test suite for the exercise
- `.mocharc.json` configuration for running tests
- `package.json, package-lock.json` project dependencies
- `tsconfig.json` TypeScript configuration for the exercise
- `README.md` the instructions you're reading right now!

## Notes

1. Feel to use another package manager if you'd like
2. You can use plain JS if you're not comfortable with TypeScript
3. Types and interfaces can be found in `src/supporting.ts`
4. Running (and passing) the tests is optional
