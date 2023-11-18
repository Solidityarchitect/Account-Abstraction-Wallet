![2370170030![23711700302549_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/1c2bc787-fdee-43b9-abd4-58001d2866e0)
![23711700302549_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/cde21b7d-4a95-4fb0-a001-5933e4f8f1a2)
![23721700302554_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/a48537f1-8afb-48a7-918e-51c57b37fb15)
![23731700302559_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/78c89508-4a79-4098-9b47-4b8901cd0f9b)


```shell
git clone https://github.com/Solidityarchitect/cross-chain-erc20.git
yarn
settings .env
yarn hardhat run scripts/01-deploy-lp.js --network "yourtestnet"
yarn hardhat run scripts/02-deploy-receiver.js --network "yourtestnet"
yarn hardhat run scripts/03-transferowner.js --network "yourtestnet"  (Pass in the deployed DestChainReceiverAddress and liquidityPoolAddress)
yarn hardhat run scripts/04-deploy-sender.js --network "yourtestnet"
```
