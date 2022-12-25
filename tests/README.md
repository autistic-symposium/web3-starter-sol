## tests in solidity

### tl; dr

#### assert vs. require

* Assert() should only be used to test for internal errors, and to check invariants.
* Require() should be used to ensure valid conditions are met that cannot be detected until execution time.
* You may optionally provide a message for require, but not for assert.



#### unit testing


* [Solidity-Coverage](https://github.com/sc-forks/solidity-coverage)
* [Remix tests](https://github.com/ethereum/remix-project/tree/master/libs/remix-tests)
* [OpenZeppelin test helpers](https://github.com/OpenZeppelin/openzeppelin-test-helpers)
* [foundry forge tests](https://github.com/foundry-rs/foundry/tree/master/forge)
* [etheno](https://github.com/crytic/etheno)



<br>

---

### resources


* [how to mock solidity contracts](https://ethereum.org/en/developers/tutorials/how-to-mock-solidity-contracts-for-testing/)
* [truffle smart contract test framework](https://ethereum.org/en/developers/tutorials/how-to-mock-solidity-contracts-for-testing/)
* [in-depth guide to testing ethereum smart contracts](https://iamdefinitelyahuman.medium.com/an-in-depth-guide-to-testing-ethereum-smart-contracts-2e41b2770297)
* [how to test smart contracts](https://betterprogramming.pub/how-to-test-ethereum-smart-contracts-35abc8fa199d)
