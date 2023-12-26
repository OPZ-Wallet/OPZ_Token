# OPZ Token Overview

## Contract Details
`OPZToken.sol` is an ERC20 standard smart-contract named OPZ. The contract inherits from the ERC20 and ERC20Permit contracts. The contract mints 1,000,000,000 OPZ tokens to the address that deploys the contract, and does not have the ability to mint any more tokens after the deployment. 

- <b>Network:</b> Ethereum Network (ERC20)
- <b>Token Name:</b> OPZ Token
- <b>Token Symbol:</b> OPZ
- <b>Total Supply:</b> 1,000,000,000 (1 billion)
- <b>Decimals:</b> 18

### Solidity
- <b>License:</b> `SPDX-License-Identifier: MIT`
- <b>Solidity Version:</b> `pragma solidity ^0.8.20;`
- <b>The OPZToken.sol contract imports the following OpenZeppelin smart-contracts:</b><br>
`import "@openzeppelin/contracts/token/ERC20/ERC20.sol";`<br>
`import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Permit.sol";`<br>
