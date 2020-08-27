# proof-of-concept-public
This is the publicly available source code for Noether PoC.


## Smart Contracts

### Basic ERC20
The `BasicERC20.sol` smart contract is a trimmed version of the OpenZeppelin standard ERC20 contract [(GitHub)](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol). The constructor function was modified to allocate an initial total supply entirely to the contract deployer.

The contract was compiled using the Remix [online compiler](https://remix.ethereum.org/).