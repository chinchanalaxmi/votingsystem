# Decentralized Voting System

This is a simple decentralized voting system built using Solidity smart contracts. It allows an admin to add candidates and users to vote once for their preferred candidate.

## Features

- Add candidates (admin only)
- Vote for a candidate (once per address)
- View vote counts
- Smart contract deployed on Ethereum-compatible networks

## Smart Contract

The main contract is `Voting.sol`. It includes:
- Candidate registration
- Voter registration and voting logic
- Vote count tracking

## How to Use

1. Clone the repository:

2. Open the `Voting.sol` file in [Remix IDE](https://remix.ethereum.org/)

3. Compile and deploy the contract using Remix

4. Interact with the functions:
- `addCandidate(name)`
- `vote(candidateId)`
- `getVotes(candidateId)`

## License

MIT
