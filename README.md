# Eth Beginner

This program teach you in eht beginner course which indicates and creates how will you code to have tokens and how it works 

## Description

This is where you can learn how to start knowing the eth as a beginner that leads you in advance eth that can expand ur knowledge into this ethereum.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Filomeno.sol). and type your code into the file:

```javascript
 SPDX-License-Identifier MIT
pragma solidity 0.8.18;

contract MyToken {

     public variables here
    string public tokenName = META;
    string public tokenAbbrv = MTA;
    uint public totalSupply = 0;

     mapping variable here
    mapping(address = uint) public balances;
     mint function
    function mint(address _address, uint _value) public {
        totalSupply += _value;
        balances[_address] += _value;
    }
     burn function
    function burn(address _address, uint _value) public {
        if (balances[_address] = _value){
            totalSupply -= _value;
            balances[_address] -= _value;
        }
    }
}


```

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile Filomeno.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "FIlomeno" contract from the dropdown menu, and then click on the "Deploy" button.


## Authors

Filomeno, Mary Rose T.
[@metacraftersio](https://twitter.com/metacraftersio)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
