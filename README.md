# WhileLoop.sol
WhileLoop.sol
pragma solidity ^0.8.20;
contract WhileLoop {
    function sum(uint n) public pure returns(uint){
        uint i=1;
        uint s;
        while(i<=n){
            s+=i;
            i++;
        }
        return s;
    }
}
