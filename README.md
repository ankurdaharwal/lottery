# lottery
### On-chain Lottery Smart with Random Number VRF Consumer using ChainLink VRF

[Documentation]()

## Setup
- `yarn`
- `yarn global add hardhat-shorthand`

## Run local node
- `yarn node`

## Environment File (.env)
- Configure the following environment variables on a .env in the package root:
  - Mnemonic - Deployment Owner(s)
  - Lottery Participant Entry Fee
  - Owner Fee

## Compile & migrate (Deploy) Contracts
- `yarn deploy` (Optional --network)

## Run Tests
- `yarn test`