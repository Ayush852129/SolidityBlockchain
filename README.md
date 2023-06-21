# SolidityBlockchain


This is a Solidity smart contract for a custom token called MyToken.

## Requirements

1. The contract has public variables that store the details about the coin:
   - Token Name: "MetaCraft"
   - Token Abbreviation: "MX"
   - Total Supply: 0

2. The contract includes a mapping of addresses to balances (`mapping(address => uint) public balances`).

3. The contract has a `mint` function that takes two parameters: an address and a value. The function increases the total supply by the specified value and increases the balance of the "sender" address by that amount.

4. The contract has a `burn` function that works the opposite of the `mint` function. It takes an address and a value as parameters, deducts the value from the total supply, and from the balance of the "sender" address.

5. The `burn` function includes conditionals to ensure that the balance of the "sender" is greater than or equal to the amount that is supposed to be burned.

# usage

Deploy the MyToken contract on the Ethereum network.

Use the mint function to increase the total supply and the balance of a specific address.

Use the burn function to decrease the total supply and the balance of a specific address, with appropriate validations.

Please note that this contract is licensed under the MIT License.

