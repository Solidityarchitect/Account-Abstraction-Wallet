
![23701700302535_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/7943f92f-e3f8-40fc-9ea4-6252dbb19431)
![23711700302549_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/62796084-89ba-4441-b3ad-bc18447adc78)
![23721700302554_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/c278d1b2-bbad-45fa-8fcf-b5e0e0fda55e)
![23731700302559_ pic](https://github.com/Solidityarchitect/cross-chain-erc20/assets/125990317/e249e48b-5be0-45d9-bc33-df0625181718)


```shell
git clone https://github.com/Solidityarchitect/cross-chain-erc20.git
yarn
settings .env
yarn hardhat run scripts/01-deploy-lp.js --network "yourtestnet"
yarn hardhat run scripts/02-deploy-receiver.js --network "yourtestnet"
yarn hardhat run scripts/03-transferowner.js --network "yourtestnet"  (Pass in the deployed DestChainReceiverAddress and liquidityPoolAddress)
yarn hardhat run scripts/04-deploy-sender.js --network "yourtestnet"
```
