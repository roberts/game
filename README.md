# Super Bowl Blockchain Game ($GAME)

This repository holds the codebase for the Super Bowl Blockchain Game on Ethereum. The tokenomics of the game is divided into 3 smart contracts:

- [$GAME](https://github.com/roberts/game/blob/main/game.sol)
- [$CHIEFS](https://github.com/roberts/game/blob/main/chiefs.sol)
- [$NINERS](https://github.com/roberts/game/blob/main/niners.sol)

## Tokenomics

Each of the smart contracts contains 100,000,000 tokens which are pooled together with Ethereum through the Uniswap DEX. The following liquidity pools will be created in this order:

- V3 Pairing w/ 25% $GAME & 50% $CHIEFS
- V3 Pairing w/ 25% $GAME & 50% $NINERS
- V2 Pool w/ 50% $GAME & 2 ETH
- V2 Pool w/ 50% $CHIEFS & 2 ETH (delayed 1 hour after $GAME pool)
- V2 Pool w/ 50% $NINERS & 2 ETH (delayed 1 hour after $CHIEFS pool)

100% of token supply in each contract are launching into Liquidity Pools for true fair launch. Contract Addresses will be provided 24 hours in advance to the public. 
