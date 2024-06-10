# Awesome Preconfirmations [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources, research, and implementations related to preconfirmations in the Ethereum ecosystem.

## Table of Contents
- [Introduction](#introduction)
- [Research and Discussion](#research-and-discussion)
- [Implementations](#implementations)
- [Based Rollup](#based-rollups)
- [Related Concepts](#related-concepts)
- [Contributing](#contributing)

## Introduction
Preconfirmations are a mechanism that allows block proposers to commit to a block's contents before it is included in the blockchain. Follow the Ethereum Sequencing and Preconfirmations calls [here](https://www.youtube.com/watch?v=jrm4ZUoj9xY&list=PLJqWcTqh_zKHDFarAcF29QfdMlUpReZrR).

## Research and Discussion
- [Based Preconfirmations](https://ethresear.ch/t/based-preconfirmations/17353) - The original post introduces the concept of based preconfirmations.
- [Eth Research: Preconfirmations Tag](https://ethresear.ch/tag/preconfirmations) - A collection of research discussions and proposals related to preconfirmations on the Ethereum Research forum.
- [Value-Capturing Based Rollups with Preconfirmations](https://collective.flashbots.net/t/value-capturing-based-rollups-with-based-preconfirmations/2884) - A protocol which allows for based rollups to capture value generated from block building with preconfirmations.

## Implementations
- [Bolt](https://chainbound.github.io/bolt-docs/) - Bolt enables Ethereum block proposers to provide credible commitments about the contents of their blocks.
- [Espresso](https://docs.espressosys.com/sequencer) - Espresso allows applications to sell their sequencing rights through an open marketplace. 
- [mev-commit](https://docs.primev.xyz/) - A credible commitment network used for preconfirmations & more.

## Based Rollups
- [KeySpace](https://docs.key.space/) - Keyspace is a cross-chain key/value store for smart wallet keys and other configurations.
- [Taiko](https://docs.taiko.xyz/) - Taiko is an EVM-based rollup.
- [Spire](https://www.spire.dev/) - Spire is a based appchain framework.

## Related Concepts
- [Proposer-Builder Separation (PBS)](https://github.com/ethereum/builder-specs) - A related concept that separates the roles of proposers and builders in the Ethereum consensus layer.
- [MEV-Boost](https://boost.flashbots.net/) - A middleware that outsources block building to a network of builders, enabling proposer commitments.

## Contributing
Contributions to this awesome list are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.
