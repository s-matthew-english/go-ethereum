# GoEthe

This is a fork of the Ethereum protocol's official golang implementation.
The purpose of this code base is to provide a framework for testing the effectiveness of the EVM, particularly it has been augmented to track the execution time of individual opcodes.


## Commands: 

Start with this command:

```
make all

./build/bin/geth datadir=/Users/s.matthew.english/Library/Ethereum/testnet console
```

As your node/EVM runs it will generate lots of output text so consider piping the output to a file.


## Resources:

* https://ethereum.stackexchange.com/questions/23638/analysis-of-the-opcodes-used-in-smart-contract-execution-on-ropsten-geth

* https://ethereum.stackexchange.com/questions/23830/geth-console-flag-option-to-output-all-opcodes-executed-in-call-to-contract-or-f

* https://ethereum.stackexchange.com/questions/23858/evaluation-of-execution-speeds-for-various-opcodes-in-evm

* https://ethereum.stackexchange.com/questions/23917/log-output-of-modified-function-to-geth-console

