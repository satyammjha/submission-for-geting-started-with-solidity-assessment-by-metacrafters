**MyToken Smart Contract**
**Overview**
MyToken is a simple ERC-20 compatible smart contract written in Solidity. It supports minting and burning of a custom token named SATYAMMJHA (abbreviation: SJH).

**Contract Details**
Token Name: SATYAMMJHA
Token Abbreviation: SJH
Compiler Version: 0.8.18
Functions
mint(address _address, uint256 _value): Mints _value tokens to _address.
burn(address _address, uint256 _value): Burns _value tokens from _address if the balance is sufficient.
Usage
Minting Tokens
solidity
Copy code
myToken.mint(0xYourAddress, 1000);
Burning Tokens
solidity
Copy code
myToken.burn(0xYourAddress, 500);
**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Author**
Satyam Jha

