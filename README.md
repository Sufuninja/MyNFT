# MyNFT
Etherum.org tut project on how to write and deploy an nft.
Following the [Ethereum.org Tutorial](https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/)
In this test project I am using the Goerli Ethereum test network instead of the Ropsten network because the Ropsten network has been deprecated. 

Create .env file with your Etherum network PRIVATE_KEY and your Alchemy API_URL
```
npm install
npx hardhat compile
npx hardhat --network goerli run scripts/deploy.js
```
Upload file(image) and file(metadata) to [Pinata](https://pinata.cloud)
[Pinata API Docs](https://docs.pinata.cloud/)
```
node ./scripts/mint-nft.js
```
