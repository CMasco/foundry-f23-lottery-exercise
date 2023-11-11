# Provably Random Raffle Contracts

## About

this code is to create a provably random smart contract

## What we want it to do?

1. Users can enter by paying for a ticket
    1. Ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
    1. And this will be done programatically
3. Using Chainlink VRF and Chainlink automation
    1. LINK VRF -> Randomness
    2. LINMK Automation -> time based trigger


## Testing

1. write deploy scripts
2. write tests so:
    1. works on local chain
    2. works on testnet
    3. works on mainnet