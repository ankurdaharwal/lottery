# Lottery
### On-chain Lottery Smart with Random Number VRF Consumer using ChainLink VRF

[Documentation](https://ipfs.io/ipfs/QmPJTrZzyPFt3HhMg8umtPGyq4PY3dvz96zUo8RUJ6YbbP)

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


![image](https://user-images.githubusercontent.com/25655858/120903480-e842d000-c678-11eb-8731-56906fad5b8f.png)

## Run Tests
- `yarn test`
