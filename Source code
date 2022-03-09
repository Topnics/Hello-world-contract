//SPDX-License-Identifier: MIT
pragma solidity ^0.8.11;

contract Helloworld {
    string public name;
    string public greetingPrefix = "Hello world, I am ";

    constructor (string memory initialName) {
        name=initialName;
    }
    function setName(string memory newName) public {
        name = newName; 
    }
    function getHelloworld() public view returns (string memory){
        return string(abi.encodePacked(greetingPrefix, name));
    }
}    
