// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract HelloWorld {

    string public message = "Hello World";

    constructor() {
        message = "Welcome to AIDS";
    }

    function setMessage(string memory _message) public {
        message = _message;
    }
}
