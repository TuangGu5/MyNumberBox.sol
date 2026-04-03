# MyNumberBox.sol
MyNumberBox.sol1
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract MyNumberBox {
    uint public number;

    function setNumber(uint _num) public {
        number = _num;
    }
}
