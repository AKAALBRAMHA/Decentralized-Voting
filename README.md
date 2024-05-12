# Dvoting Smart Contract

## Overview

Dvoting is a decentralized voting smart contract implemented in Solidity. It allows for the creation of proposals and enables registered voters to vote on these proposals within a specified time frame.

## Features

- **Voter Registration:** Users can register themselves as voters to participate in the voting process.
- **Proposal Submission:** Registered voters can submit proposals during the proposal submission period.
- **Voting:** Registered voters can cast their votes for proposals during the voting period.
- **Proposal Winner Determination:** The contract automatically determines the winning proposal based on the highest number of votes received.
- **Voter Deregistration:** Voters can deregister themselves if needed.

## Getting Started

### Prerequisites

- **Solidity Compiler:** Ensure you have a Solidity compiler installed to compile the contract code.
- **Ethereum Network:** Deploy the contract to an Ethereum network (e.g., Rinkeby, Ropsten, or a local development network).

### Deployment

1. Compile the Solidity contract using a Solidity compiler.
2. Deploy the compiled contract to an Ethereum network of your choice.
3. Interact with the deployed contract using a compatible Ethereum wallet or through a web3.js application.

### Interacting with the Contract

1. **Register as a Voter:** Call the `getRegister` function to register yourself as a voter.
2. **Submit a Proposal:** During the proposal submission period, call the `propose` function to submit a new proposal.
3. **Vote:** During the voting period, use the `vote` function to cast your vote for a proposal.
4. **Check Proposal Count:** Use the `getProposalscount` function to get the total number of proposals.
5. **Deregister:** If needed, call the `deregister` function to deregister yourself as a voter.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
