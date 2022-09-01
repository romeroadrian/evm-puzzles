# EVM puzzles

A collection of EVM puzzles. Each puzzle consists on sending a successful transaction to a contract. The bytecode of the contract is provided, and you need to fill the transaction data that won't revert the execution.

## How to play

Clone this repository and install its dependencies (`npm install` or `yarn`). Then run:

```
npx hardhat play
```

And the game will start.

In some puzzles you only need to provide the value that will be sent to the contract, in others the calldata, and in others both values.

You can use [`evm.codes`](https://www.evm.codes/)'s reference and playground to work through this.

## Solutions

1. https://www.evm.codes/playground?callValue=8&unit=Wei&callData=&codeType=Bytecode&code=%273456FDFDFDFDFDFD5B00%27_
2. https://www.evm.codes/playground?callValue=4&unit=Wei&callData=&codeType=Bytecode&code=%2734380356FDFD5B00FDFD%27_
3. https://www.evm.codes/playground?callValue=0&unit=Wei&callData=0x00000000&codeType=Bytecode&code=%273656FDFD5B00%27_
4. https://www.evm.codes/playground?callValue=6&unit=Wei&callData=&codeType=Bytecode&code=%2734381856FDFDFDFDFDFD5B00%27_
5. https://www.evm.codes/playground?callValue=16&unit=Wei&callData=&codeType=Bytecode&code=%2734800261010014600C57FDFD5B00FDFD%27_
6. https://www.evm.codes/playground?callValue=0&unit=Wei&callData=0x000000000000000000000000000000000000000000000000000000000000000a&codeType=Bytecode&code=%2760003556FDFDFDFDFDFD5B00%27_
7. https://www.evm.codes/playground?callValue=0&unit=Wei&callData=0x60016000f3&codeType=Bytecode&code=%2736600080373660006000F03B600114601357FD5B00%27_
8. https://www.evm.codes/playground?callValue=0&unit=Wei&callData=0x63000000fd6000526001601ff3&codeType=Bytecode&code=%2736600080373660006000F0600080808080945AF1600014601B57FD5B00%27_
9. https://www.evm.codes/playground?callValue=2&unit=Wei&callData=0x00000000&codeType=Bytecode&code=%2736600310600957FDFD5B343602600814601457FD5B00%27_
10. https://www.evm.codes/playground?callValue=15&unit=Wei&callData=0x000000&codeType=Bytecode&code=%2738349011600857FD5B3661000390061534600A0157FDFDFDFD5B00%27_
