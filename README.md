OP Stack L2 Rollup Setup (Quick Summary)

This guide explains how to deploy your own Optimism (OP Stack) L2 rollup testnet.

You’ll build:

L1 contracts on Sepolia testnet

op-geth (execution client)

op-node (consensus client)

op-batcher, op-proposer, op-challenger

Quick Setup (Recommended):

git clone https://github.com/ethereum-optimism/docs.git
cd docs/create-l2-rollup-example
cp .example.env .env      # edit with RPC URL, private key
make init
make setup
make up
make test-l1
make test-l2
make status


This runs a complete L2 testnet with all OP Stack components via Docker.
